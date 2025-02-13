# 👋 Coxy

18-year-old fullstack developer into **pentesting, networking, and cybersecurity**.  

## 🚀 Tech Stack

### Languages
- **Rust** 🦀
- **Python** 🐍
- **JavaScript** ⚡
- **Go** 🏎️

### Frameworks & Tools
- **React**, **Next.js**
- **Flask**, **SQL**
- **Git**

## 📬 Contact
[![Discord](https://img.shields.io/badge/Discord-coxy.57-7289DA?style=for-the-badge&logo=discord)](https://discord.com/)  

## 🔥 GitHub Stats
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=1coxy57&theme=tokyonight&show_icons=true&hide_border=true&count_private=true" height="165">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=1coxy57&theme=tokyonight&hide_border=true" height="165">
</p>

```rust
struct Languages {
    languages: Vec<String>,
}

impl Languages {
    fn new() -> Self {
        Languages {
            languages: vec![
                String::from("Rust"),
                String::from("Python"),
                String::from("JavaScript"),
                String::from("Go"),
            ],
        }
    }

    fn display(&self) {
        for language in &self.languages {
            println!("{}", language);
        }
    }
}

fn main() {
    let prog_languages = Languages::new();
    prog_languages.display();
}
