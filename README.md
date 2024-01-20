### Hi there 👋

![GIF](https://media.giphy.com/media/gvfpZrR54qd56/giphy.gif)


My Name is Devesh!   
I'm 23  

fn main() 
{
  let mut dx: u64 = 0x77E435B08;
  while dx != 0 {
    let s = ((dx >> 3) & 7) * 8;
    let e = (0x726F6C6564574820u64 >> s) & 0xFF;
    print!("{}", e as u8 as char); 
    dx >>= 3;
    }
  println!();
}
