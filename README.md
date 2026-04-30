# Cocktails Common Library

A shared .NET library containing common models, interfaces, and utilities used across the Cocktails application ecosystem. This library is published as a NuGet package for easy consumption by other projects.

## 🎯 Purpose

This library provides shared functionality and models that are used across different parts of the Cocktails application, ensuring consistency and reducing code duplication. It serves as a central location for common code that needs to be shared between the API and other services.

## 📦 Package Information

- **Package Name**: Cocktails.Common
- **Framework**: .NET 9.0
- **Authors**: Ronaldo Vecchi
- **Company**: Cezzis
- **Repository**: [GitHub Repository](https://github.com/mtnvencenzo/cezzis-com-cocktails-common)

## 🛠️ Components

### Email Models
- `EmailMessage`: Complete email message model with support for:
  - To, CC, BCC recipients
  - Subject and body
  - Attachments
  - Priority levels
  - Correlation tracking
- `EmailAddress`: Email address model with display name support
- `EmailAttachment`: Model for email attachments
- `EmailPriority`: Enum for email priority levels

### Utilities
- `EventSerializer`: JSON serialization utilities with consistent configuration
- `CocktailsMonikers`: Common identifiers and constants

## 📁 Project Structure

```
src/
└── Cocktails.Common/           # Main library project
    ├── Emails/                # Email-related models
    └── Utilities/            # Shared utilities
test/
│   └── Cocktails.Common.Unit.Tests/ # Unit tests
└── README.md
```

## 🚀 Development

### Prerequisites
- .NET Core SDK 9.0
- Visual Studio 2022
- NuGet CLI

### Building
```bash
# Restore dependencies
dotnet restore

# Build the solution
dotnet build

# Run tests
dotnet test
```

## 📄 License

This project is proprietary software. All rights reserved. 