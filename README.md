```go
package main

import "fmt"

type Developer struct {
    Code              []string
    Interests         []string
    OperatingSystems  []string
    ToolsUsed         []string
    IDEs              []string
}

func main() {
    _9dl := Developer{
        Code:             []string{"Golang", "C#", "Next.js", "Python", "C++"},
        Interests:        []string{"Cybersecurity", "Reversing", "Backend Development", "Frontend Development"},
        OperatingSystems: []string{"Windows 11", "Kubuntu"},
        ToolsUsed:        []string{"Git Bash", "VMWare", "MobaXterm", "PuTTY"},
        IDEs:             []string{"VS (C#)", "VS Code (Web & Go)", "Webstorm (Web)", "Goland (Go)", "CLion (C++)"},
    }

    fmt.Printf("👋 Hello! I'm 9dl, a developer.\n")
    fmt.Printf("💻 Code: %v\n", _9dl.Code)
    fmt.Printf("🌐 Interests: %v\n", _9dl.Interests)
    fmt.Printf("🖥️ Operating Systems: %v\n", _9dl.OperatingSystems)
    fmt.Printf("🛠️ Tools Used: %v\n", _9dl.ToolsUsed)
}
```
