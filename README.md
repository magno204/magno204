# Carlos Pineda Salazar

<!--
**magno204/magno204** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I'm currently working on ...
- 🌱 I'm currently learning ...
- 👯 I'm looking to collaborate on ...
- 🤔 I'm looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
:computer: **Desarrollador de Software**

⚙️ C# · .NET · Angular

📍 Medellín, Colombia

💼 +11 años creando software

🌱 Aprendiendo constantemente 🤓

### :zap: Actividad reciente
<!--RECENT_ACTIVITY:start-->
1. ⬆️ Pushed undefined commit(s) to [magno204/magno204](https://github.com/magno204/magno204)<br>
2. ⬆️ Pushed undefined commit(s) to [magno204/magno204](https://github.com/magno204/magno204)<br>
3. ⬆️ Pushed undefined commit(s) to [magno204/cdn_prompts_guia](https://github.com/magno204/cdn_prompts_guia)<br>
4. 💪 Opened PR [#1](undefined) in [magno204/cdn_prompts_guia](https://github.com/magno204/cdn_prompts_guia)<br>
5. ⬆️ Pushed undefined commit(s) to [magno204/cdn_prompts_guia](https://github.com/magno204/cdn_prompts_guia)<br>
<!--RECENT_ACTIVITY:end-->
<!--RECENT_ACTIVITY:last_update-->
Last Updated: Saturday, April 4th, 2026, 12:41:07 PM
<!--RECENT_ACTIVITY:last_update_end-->

<!--START_SECTION:activity-->

<!--END_SECTION:activity-->


```csharp
// 🚀 Carlos Pineda Salazar — .NET 9 | C# 13

var dev = new Developer("Carlos Pineda Salazar", "Senior Software Developer", 11);

dev.Backend =    ["⚙️ C#", "⚙️ .NET 8/9", "⚙️ ASP.NET Core", "⚙️ Web API REST", "⚙️ CQRS", "⚙️ Clean Architecture"];
dev.Frontend =   ["🎨 Angular 17+", "🎨 TypeScript", "🎨 HTML5", "🎨 CSS3"];
dev.Databases =  ["🗄️ SQL Server", "🗄️ MySQL"];
dev.DevOps =     ["🐳 Docker", "🔀 Git", "🐙 GitHub", "🦊 GitLab", "🔄 CI/CD"];
dev.Testing =    ["🧪 xUnit", "🧪 Mock", "🧪 Unit Testing"];
dev.SoftSkills = ["🤝 Trabajo en equipo", "💬 Comunicación efectiva", "🧠 Resolución de problemas"];

dev.PrintProfile();

// Output:
// 👨‍💻 Carlos Pineda Salazar
// 💼 Senior Software Developer · 11+ años de experiencia
//
// ⚙️ Backend       ⚙️ C# · ⚙️ .NET 8/9 · ⚙️ ASP.NET Core · ⚙️ Web API REST · ⚙️ CQRS · ⚙️ Clean Architecture
// 🎨 Frontend      🎨 Angular 17+ · 🎨 TypeScript · 🎨 HTML5 · 🎨 CSS3
// 🗄️ Databases     🗄️ SQL Server · 🗄️ MySQL
// 🐳 DevOps        🐳 Docker · 🔀 Git · 🐙 GitHub · 🦊 GitLab · 🔄 CI/CD
// 🧪 Testing       🧪 xUnit · 🧪 Mock · 🧪 Unit Testing
// 🤝 Soft Skills   🤝 Trabajo en equipo · 💬 Comunicación efectiva · 🧠 Resolución de problemas

public record Developer(string Name, string Role, int YearsOfExperience)
{
    public List<string> Backend { get; set; } = [];
    public List<string> Frontend { get; set; } = [];
    public List<string> Databases { get; set; } = [];
    public List<string> DevOps { get; set; } = [];
    public List<string> Testing { get; set; } = [];
    public List<string> SoftSkills { get; set; } = [];

    public void PrintProfile()
    {
        Console.WriteLine($"👨‍💻 {Name}");
        Console.WriteLine($"💼 {Role} · {YearsOfExperience}+ años de experiencia");
        Console.WriteLine();
        PrintSection("⚙️ Backend", Backend);
        PrintSection("🎨 Frontend", Frontend);
        PrintSection("🗄️ Databases", Databases);
        PrintSection("🐳 DevOps", DevOps);
        PrintSection("🧪 Testing", Testing);
        PrintSection("🤝 Soft Skills", SoftSkills);
    }

    private void PrintSection(string title, List<string> items)
        => Console.WriteLine($"{title,-15} {string.Join(" · ", items)}");
}
```
