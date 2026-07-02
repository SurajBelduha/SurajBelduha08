public class SurajPrajapati : SoftwareEngineer
{
    public string Name        => "Suraj Prajapati";
    public string Role        => ".NET Core & C# Backend Developer";
    public int    Experience  => 4; // years+
    public string Location    => "India 🇮🇳";
    public string Specialty   => "FinTech | Payment Gateway | Scalable APIs";

    public string[] CurrentWork => new[] {
        "Building payment systems at Jigrotech Solutions",
        "Integrating Kotak Bank, Payol, SolitPay, SafePay APIs",
        "Designing Clean Architecture & CQRS patterns"
    };

    public string[] Strengths => new[] {
        "ASP.NET Core 8",  "C#",            "Dapper",
        "SQL Server",       "EF Core",       "React",
        "Clean Architecture","REST APIs",    "Payment Gateways"
    };

    public string[] Learning => new[] {
        "Azure Cloud Services",
        "Docker & Containerization",
        "Microservices Architecture"
    };

    public bool OpenToWork      => true;
    public bool OpenToFreelance => true;
}
