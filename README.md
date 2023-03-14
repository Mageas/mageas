<h1 align="center">
  Hello, I'm Arnaud Gaydamour! <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="35px">
</h1>

I am currently living in Lyon, France and I am studying again. I am self-taught and I am learning programming through small personal projects in my free time.

<br>

<p>
<div align="center">
  <a href="https://www.linkedin.com/in/arnaud-gaydamour-0aa4041a4/"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="Linkedin" /></a>&nbsp;
  <a href="https://gitea.heartnerds.org/Mageas"><img src="https://img.shields.io/badge/gitea-%609a2100.svg?&style=for-the-badge&logo=gitea&logoColor=white" alt="Youtube" /></a>&nbsp;
  <a href="https://www.youtube.com/@mageas557"><img src="https://img.shields.io/badge/youtube-%23FF0000.svg?&style=for-the-badge&logo=youtube&logoColor=white" alt="Youtube" /></a>&nbsp;
</div>
</p> 

```rust
struct Identity<'a> {
    name: &'a str,
    username: &'a str,
    location: &'a str,
    web: &'a str,
}

struct Skill<'a> {
    name: &'a str,
    list: Vec<&'a str>,
}

fn main() {
    let me = Identity {
        name: "Arnaud Gaydamour",
        username: "Mageas",
        location: "Lyon, France",
        web: "https://gitea.heartnerds.org/Mageas",
    };
    
    let my_skills = vec![
        Skill {
            name: "Languages",
            list: vec!["Rust", "Shell", "Python", "Javascript", "HTML", "CSS"],
        },
        Skill {
            name: "Frameworks",
            list: vec!["Svelte", "Laravel"],
        },
        Skill {
            name: "Operating system",
            list: vec!["Linux", "Windows"],
        },
        Skill {
            name: "Devops",
            list: vec!["Docker", "Nginx"],
        },
        Skill {
            name: "Tools",
            list: vec!["Git", "Vim", "VSCode", "Emacs"],
        },
    ];
}
```
