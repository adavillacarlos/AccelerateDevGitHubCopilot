# Library App

## Description
Library App is a console-based application for managing a library system. It allows users to search for patrons, view patron details, manage loans, and more. The application is built using .NET and follows a modular architecture with clear separation of concerns.

## Project Structure
- `AccelerateDevGitHubCopilot.sln`
- `README.md`
- `src/`
  - `Library.ApplicationCore/`
    - `Library.ApplicationCore.csproj`
    - `Entities/`
    - `Enums/`
    - `Interfaces/`
    - `Services/`
  - `Library.Console/`
    - `appSettings.json`
    - `CommonActions.cs`
    - `ConsoleApp.cs`
    - `ConsoleState.cs`
    - `Library.Console.csproj`
    - `Json/`
  - `Library.Infrastructure/`
    - `Library.Infrastructure.csproj`
    - `Data/`
- `tests/`
  - `UnitTests/`
    - `LoanFactory.cs`
    - `UnitTests.csproj`

## Key Classes and Interfaces
- **Library.ApplicationCore**
  - `Entities/`
    - `Patron`
    - `Loan`
    - `Book`
    - `Author`
  - `Enums/`
    - `ConsoleState`
    - `CommonActions`
  - `Interfaces/`
    - `IPatronRepository`
    - `ILoanRepository`
    - `ILoanService`
    - `IPatronService`
  - `Services/`
    - `LoanService`
    - `PatronService`
- **Library.Console**
  - `ConsoleApp`
  - `CommonActions`
  - `ConsoleState`
- **Library.Infrastructure**
  - `Data/`
    - `JsonData`
    - `JsonPatronRepository`
    - `JsonLoanRepository`

## Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/library-app.git
