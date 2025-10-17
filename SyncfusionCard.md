# 📘 Syncfusion Blazor App – Card-Based Dashboard Demo

Welcome to the **Syncfusion Blazor App**, a modular dashboard demo built around the powerful **Syncfusion Card control**. This project showcases how to scaffold reusable card components using Syncfusion’s Blazor UI library, clean architecture, and interactive server-side rendering.

The **Syncfusion Card control** is ideal for presenting structured content such as feature highlights, story cards, teaching notes, or product summaries. It supports:
- 🧩 Modular layout with headers, images, descriptions, and actions
- 🎯 Responsive design across devices and screen sizes
- ⚙️ Customizable sections including avatars, media, and footers
- 📚 Educational clarity for curriculum authors and learners

This demo is part of a broader initiative to build curriculum-ready teaching assets using Blazor and Syncfusion.

---

## 🚀 Project Overview

- **Framework**: .NET 8 Blazor Web App (Interactive Server Mode)
- **UI Library**: Syncfusion Blazor Components
- **Architecture**: Modular folders for `/Models`, `/Services`, `/Components`, and `/Pages`
- **Purpose**: Demonstrate reusable card rendering with Syncfusion for educational and business use

---

```
SyncfusionBlazorApp/
│
├── Models/               # Data models (e.g., CardFeature.cs)
├── Services/             # Data services and interfaces
├── Components/           # Reusable UI components (e.g., FeatureCard.razor)
├── Pages/                # Page-level views (e.g., CardFeatures.razor)
├── Images/               # Static assets (e.g., card-anatomy.png)
├── wwwroot/              # Public assets
├── Program.cs            # App startup and Syncfusion registration
├── App.razor             # Routing setup
└── MainLayout.razor      # Shared layout
```



Code

---

## 🧩 Syncfusion Card Anatomy

Here’s a visual breakdown of the Syncfusion Card component used in this project:

![Syncfusion Card Anatomy](Images/card-anatomy.png)

---

## 🛠 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/SyncfusionBlazorApp.git
   cd SyncfusionBlazorApp
Install dependencies

bash
dotnet restore
Register your Syncfusion license key In Program.cs, replace the placeholder:

csharp
Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("YOUR_LICENSE_KEY_HERE");
⚠️ Do not commit your license key to public repositories.

Run the project

bash
dotnet run
📚 Educational Use
This project is designed for:

Curriculum authors creating modular teaching assets

Educators showcasing UI design and storytelling

Developers learning Syncfusion and Blazor architecture

Business strategists exploring digital bundles and dashboards