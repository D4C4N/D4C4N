```CSharp
public class D4C4N
{
    public string Username { get; set; } = "D4C4N";
    public string Name { get; } = "Daniel";
    public string[] Nicknames { get; } = { "D4", "Daniel", "Dan" };
    public string FieldOfStudy { get; } = "Applied Computer Science";
    public string[] Interests { get; } = { "cats", "gaming", "music", "guitar" };
    public bool IsAlive { get; set; } = true;
    public int? Age { get; set; } = 26;

    public List<string> TechStack { get; } = new List<string>
    {
        "C", "C#", "React", "HTML", "CSS", "JavaScript"
    };

    public string FavoriteLanguage => TechStack.Contains("C#") ? "C#" : TechStack[0];

    public string Email { get; } = "dacan1508@gmail.com";

    public void Introduce()
    {
        Console.WriteLine("👋 Hey there, I'm " + Username);
        Console.WriteLine("You can call me: " + string.Join(", ", Nicknames));
        Console.WriteLine($"🎓 I'm currently studying: {FieldOfStudy}");
        Console.WriteLine("🎮 Outside of coding, I'm into: " + string.Join(", ", Interests));
        Console.WriteLine("🛠 Tech stack: " + string.Join(", ", TechStack));
        Console.WriteLine("💌 Reach me at: " + Email);
    }
}
```

<!---
D4c4n/D4c4n is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
