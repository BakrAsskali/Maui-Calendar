# Maui-Calendar

Maui-Calendar is a cross-platform calendar application built using .NET MAUI. This project aims to provide a simple and intuitive calendar experience for users, allowing them to manage their events and schedules seamlessly across different devices.

## Features

- **Cross-Platform Support:** Runs on Android, iOS, Windows, and macOS.
- **Event Management:** Add, edit, and delete events.
- **Month, Week, and Day Views:** Easily switch between different calendar views.
- **Notifications:** Receive reminders for upcoming events.
- **Dark Mode:** Supports both light and dark themes.

## Getting Started

### Prerequisites

- [.NET 7 SDK](https://dotnet.microsoft.com/download/dotnet/7.0)
- [Visual Studio 2022](https://visualstudio.microsoft.com/) with .NET MAUI workload installed

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/BakrAsskali/Maui-Calendar.git
   cd Maui-Calendar
   ```

2. **Restore NuGet packages:**
   ```sh
   dotnet restore
   ```

3. **Build the project:**
   ```sh
   dotnet build
   ```

4. **Run the application:**
   ```sh
   dotnet run
   ```

### Configuration

To configure the application, modify the `appsettings.json` file located in the root directory. This file contains settings for notifications, themes, and other customizable options.

## Usage

1. **Add an Event:**
    - Click on the "+" button.
    - Fill in the event details.
    - Save the event.

2. **Edit an Event:**
    - Click on the event you want to edit.
    - Modify the event details.
    - Save the changes.

3. **Delete an Event:**
    - Click on the event you want to delete.
    - Click the "Delete" button.

4. **Switch Views:**
    - Use the navigation buttons to switch between month, week, and day views.


## Acknowledgements

- [Microsoft .NET MAUI](https://github.com/dotnet/maui)
- [Syncfusion](https://www.syncfusion.com/) for their calendar control
