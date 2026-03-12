# XbrlEngine (.NET Core)

A lightweight **.NET Core class library** for parsing and viewing **XBRL (eXtensible Business Reporting Language)** documents.  
This library enables applications to read XBRL instance documents and extract structured financial data such as facts, contexts, and units.

The project is designed to be integrated into **financial reporting systems, regulatory applications, and analytics platforms** that need to process XBRL files programmatically.

---

## Overview

XBRL is widely used for **digital financial reporting** by regulators and organizations.  
However, XBRL files are XML-based and require specialized processing to extract meaningful data.

This library provides reusable components that allow developers to:

- Load XBRL instance documents
- Parse facts, contexts, and units
- Navigate taxonomy elements
- Extract financial data programmatically

The library can be integrated into **web applications, desktop applications, APIs, or background services**.

---

## Features

- Parse XBRL instance documents
- Extract financial facts
- Context and period handling
- Unit parsing
- Taxonomy element mapping
- Error handling for invalid XBRL documents
- Lightweight and dependency-friendly
- Designed for integration with other .NET applications

---

## Technology Stack

- **.NET Core**
- **C#**
- **System.Xml / LINQ to XML**

Compatible with:

- NET 8+

---

## Installation

### Using NuGet (Recommended)

```bash
dotnet add package XbrlEngine
```

### Manual Installation

#### Clone the repository
```bash
git clone https://github.com/your-org/xbrl-viewer-library.git
```
#### Build the project
```bash
dotnet build
```
Reference the compiled DLL in your application.
