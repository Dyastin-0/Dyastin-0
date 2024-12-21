# Hi there, I'm Dyastin.

a passionate developer building projects with modern web technologies. I enjoy crafting web applications, and continuously learning new technologies to enhance my skills.

📖 Studies at [Colegio de Montalban](https://pnm.edu.ph)

🛠️ I am currently crafting a backend with Go.

## A little more about me

```go
type Profile struct {
    Name           string
    About          string
    CurrentProject struct {
        Name       string
        Repository String
        URL        string
        Desc string
    }
    Contact []struct {
        Type string
        Info string
    }
    Tools map[string][]string
}

dyastin := Profile{
    Name:  "Justine Paralejas",
    About: "I enjoy crafting web apps.",
    CurrentProject: struct {
        Name       string
        Repository string
        URL        string
        Desc       string
    }{
        Name:       "Filespace",
        Repository: "https://github.com/Dyastin-0/filespace",
        URL:        "https://filespace.dyastin.tech",
        Desc:       "A simple cloud storage.",
    },
    Contact: []struct {
        Type string
        Info string
    }{
        {Type: "Email", Info: "mail@dyastin.tech"},
    },
    Tools: map[string][]string{
        "Backend": {
            "Node.js", "Express", "Go", "Socket.IO", "MongoDB", "Firebase", "AWS EC2", "Google Compute Engine", "Caddy",
        },
        "Frontend": {
            "React", "Vite", "Framer Motion", "Tailwind CSS",
        },
        "Data Fetching": {
            "SWR", "Axios",
        },
        "Version Control": {
            "Git", "GitHub",
        },
    },
}

```


