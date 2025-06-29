# 🛰️ Martian Robots – C# Coding Challenge

## 🧭 Introduction

This project is a solution to the **Martian Robots** coding challenge, implemented in **C#** with a focus on clean code, simplicity, and maintainability.

### Key Design Choices
- **Single Responsibility Principle (SRP):** Core logic is kept concise by offloading reusable operations to **extension methods**, promoting modularity and cleaner class responsibilities.
- **Readability & Maintainability:** The code is fully documented to improve readability and to help future developers quickly understand the intent.
- **Test-Driven Development:** Comprehensive **unit tests** ensure correctness by validating the sample scenarios from the challenge.
---

## 📋 Requirements

- [.NET 8 SDK](https://dotnet.microsoft.com/download)
- IDE: Visual Studio / Visual Studio Code / JetBrains Rider
- [xUnit](https://xunit.net/) – for unit testing  
- [FluentAssertions](https://fluentassertions.com/) – for expressive test assertions

---

## 🚀 Getting Started

### 📦 Installation

```bash
# 1. Clone the repository
git clone https://github.com/audreykmaidza/MARTIANROBOTS.git
cd martian-robots

# 2. Restore dependencies
dotnet restore

# 3. Build the solution
dotnet build

# 4. Run the project
dotnet run --project MartianRobots


### Running the unit tests 
1. Run the Tests in the MartianRobotTests Projects in Visual Studio or use dotnet test
🛠️ Technologies Used
	•	C# .NET 8
	•	xUnit for unit testing
	•	FluentAssertions for readable test assertions
	•	Extension Methods for logic reuse and separation of concerns

⸻

📌 Next Steps
	•	Build a frontend UI using Vue.js or React to visually simulate robot paths and lost positions.
	•	Add input validation and error handling.
	•	Add support for additional future command types (e.g., Jump, Backward).
	•	Deploy as a self-hosted or containerized RESTful API for wider usage.

⸻
