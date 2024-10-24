```go
package main

import (
    "fmt"
    "strings"
)

type Developer struct {
    Name              string
    Code              []string
    Interests         []string
    OperatingSystems  []string
    ToolsUsed         []string
    IDEs              []string
}

func (d Developer) DisplayProfile() {
    fmt.Printf("👋 Hello! I'm %s, a versatile developer with a passion for technology.\n\n", d.Name)
    
    fmt.Printf("💻 Coding Languages:\n   %s\n\n", strings.Join(d.Code, ", "))
    fmt.Printf("🌐 Areas of Interest:\n   %s\n\n", strings.Join(d.Interests, ", "))
    fmt.Printf("🖥️ Operating Systems:\n   %s\n\n", strings.Join(d.OperatingSystems, ", "))
    fmt.Printf("🛠️ Tools & Technologies:\n   %s\n\n", strings.Join(d.ToolsUsed, ", "))
    fmt.Printf("🖋️ Preferred IDEs:\n   %s\n", strings.Join(d.IDEs, ", "))
}

func main() {
    developer := Developer{
        Name:             "9dl",
        Code:             []string{"Go (Golang)", "C#", "Next.js", "Python", "C++"},
        Interests:        []string{"Cybersecurity", "Reverse Engineering", "Backend Development", "Frontend Development & UI/UX"},
        OperatingSystems: []string{"Windows 11 with WSL2 (Kali Linux, Ubuntu)"},
        ToolsUsed:        []string{"Git Bash", "VMware Workstation", "MobaXterm", "PuTTY", "Postman API Platform"},
        IDEs:             []string{"JetBrains WebStorm", "JetBrains GoLand", "JetBrains CLion" "JetBrains Rider" "JetBrains Fleet"},
    }

    developer.DisplayProfile()
}
```
Visitor Counter: ![](https://profile-counter.glitch.me/9dl/count.svg)
