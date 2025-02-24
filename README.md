![header](https://capsule-render.vercel.app/api?type=waving&color=auto&height=220&section=header&text=Wahel&fontSize=60&animation=fadeIn&fontAlignY=38&desc=Web%20Development%20%2F%20Student&descAlignY=51&descAlign=62)

```cs
using System.Collections.Generic; 

public class Profile
{
    private string info = "Web Developer, Student";
    private List<string> languages = new List<string>
    {
        // Prog languages
        "HTML/CSS", "JavaScript", "PHP", "C", "C++", "C#", "Python3","Bash",

        // Others (Framework, libraries)
        "Reactjs","Next.js", ".NET MAUI", "Arduino",

        // Database
        "MySQL", "PostgreSQL"
    };

    public Profile(string info, List<string> languages)
    {
        this.info = info;
        this.languages = languages;
    }
}
```
