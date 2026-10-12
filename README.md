# 👨‍💻 namespace Developer { class JeongIk : ISoftwareEngineer }

```csharp
using System;
using System.Collections.Generic;
using Microsoft.Extensions.DependencyInjection;

namespace Profile;

public class Program
{
    public static void Main()
    {
        var developer = new Developer
        {
            Name = "전정익",
            PrimaryLanguage = "C#",
            Frameworks = ["ASP.NET Core", ".NET 8/9", "Entity Framework Core"],
            Architecture = ["Clean Architecture", "Domain-Driven Design (DDD)"],
            CurrentFocus = "High-Performance Backend & Asynchronous Programming"
        };

        developer.Introduce();
    }
}
