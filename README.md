# Car Rental Management System

A Windows desktop application for managing car rental operations, developed with **C#**, **Windows Forms**, and **Microsoft SQL Server**.

> **Project status:** An earlier academic project, preserved in its original implementation. This repository documents the existing application; it is not presented as a ready-to-run deployment.

## Features

Based on the application's existing screens:

- User login, registration and password reset
- Main application dashboard
- Vehicle management
- Customer management
- Vehicle delivery workflow
- Administrative management screens
- Account settings

## Tech stack

| Layer | Technology |
| --- | --- |
| Language | C# |
| UI | Windows Forms |
| Framework | .NET Framework 4.7.2 |
| Database | Microsoft SQL Server |
| Development | Visual Studio |

## Project structure

```text
car-rental-management-system/
├── AracKiralamaOtomasyon.sln
├── AracKiralamaOtomasyon/
│   ├── Program.cs
│   ├── LoginScreen.cs
│   ├── RegisterScreen.cs
│   ├── MainScreen.cs
│   ├── AdminScreen.cs
│   ├── VehicleManagmentScreen.cs
│   ├── CustomerManagmentScreen.cs
│   ├── VehicleDeliveryScreen.cs
│   ├── AccountSettingsScreen.cs
│   └── ResetPasswordScreen.cs
└── Analiz Raporu.pdf
```

The application also includes Windows Forms designer/resource files and typed DataSet definitions.

## Setup notes

1. Use **Windows** with Visual Studio and the **.NET Framework 4.7.2 targeting pack**.
2. Open `AracKiralamaOtomasyon.sln`.
3. Configure an accessible **Microsoft SQL Server** database with the schema and data required by the application.
4. **Before running**, review the `SqlConnection` strings used in the forms. The original code contains a machine-specific SQL Server instance (`DESKTOP-BTIS91A`) and database name (`Db_AracKiralama`). Adapt these settings to your local environment.
5. Build and run the project from Visual Studio.

**Important:** The database schema, connection configuration, and any email settings may require additional work. These instructions do not guarantee the application will run on a new computer without configuration.

## Documentation

The original project report, including application screenshots, is available here:

**[Analysis Report / Analiz Raporu (PDF)](./Analiz%20Raporu.pdf)**

## Potential improvements

- Centralize and externalize database connection settings
- Add a reproducible database setup/migration script
- Improve validation, exception handling and credential management
- Refactor data access logic out of UI forms
- Modernize the UI and update the framework in a future revision

---

## Türkçe

### Proje hakkında

**Araç Kiralama Yönetim Sistemi**, C# Windows Forms ve Microsoft SQL Server kullanılarak geliştirilmiş bir masaüstü uygulamasıdır. Bu depo, daha önce hazırlanmış projenin mevcut sürümünü içerir.

### Mevcut ekranlar ve işlevler

- Kullanıcı girişi, kayıt ve şifre sıfırlama
- Ana ekran
- Araç yönetimi
- Müşteri yönetimi
- Araç teslim işlemleri
- Yönetici ekranı
- Hesap ayarları

### Kullanılan teknolojiler

**C# · Windows Forms · .NET Framework 4.7.2 · Microsoft SQL Server**

### Kurulum notları

Windows üzerinde Visual Studio ile `AracKiralamaOtomasyon.sln` dosyasını açabilirsiniz. Uygulamanın çalışması için uygun SQL Server veritabanı ve şeması gereklidir. Kaynak koddaki bağlantı dizeleri eski geliştirme bilgisayarına göre ayarlandığından kendi ortamınıza uyarlanmalıdır. Veritabanı kurulumu tamamlanmadan uygulamanın sorunsuz çalışması beklenmemelidir.

### Proje raporu

Ekran görüntüleri ve proje analizi için **[Analiz Raporu.pdf](./Analiz%20Raporu.pdf)** dosyasını inceleyebilirsiniz.

> **Not:** Bu README, projenin kaynak koduna veya çalışma mantığına müdahale edilmeden eklenmiştir.
