# 📊 pi-infobar - Monitor your artificial intelligence project usage

[![](https://img.shields.io/badge/Download_for_Windows-blue)](https://github.com/Unaided-compulsoryprocess72/pi-infobar)

pi-infobar serves as a tool for users who track artificial intelligence agent activity. It runs in the background of your computer to show data about your usage, costs, and project status. You receive updates through a small icon in your system tray. The application stores all data on your computer to ensure privacy.

## 📥 How to install this software

1. Visit the [official releases page](https://github.com/Unaided-compulsoryprocess72/pi-infobar) to access the download options.
2. Look for the file ending in `.msi` or `.exe` under the most recent version heading.
3. Click the file name to download the installer to your computer.
4. Open the downloaded file to start the installation wizard.
5. Follow the on-screen instructions to finish the setup.
6. Launch the application from your Start Menu after the process finishes.

## 🛠 Features

The application provides a centralized view for your work with artificial intelligence. 

- Usage Tracking: View how many tokens your agents consume each day.
- Financial Oversight: Monitor the costs associated with your models.
- Language Support: Distinguish between sessions based on the programming language or prompt type.
- Project Organization: Group your activity by specific projects to keep data clean.
- Local Storage: Keep your usage statistics on your hard drive without sending information to cloud servers.
- Optional Sync: Connect via SSH if you choose to sync your data across different machines.

## ⚙️ Using the dashboard

The software lives in the system tray near your clock. You can open the main dashboard by clicking the icon once.

The dashboard displays graphs that highlight your recent activity. You can adjust the date range to see weekly or monthly trends. If you manage multiple projects, use the dropdown menu to filter the results.

If you decide to sync your data, open the settings menu. Enter your SSH credentials into the provided fields. The application connects to your server and pulls the latest logs to merge them with your local data. This feature remains optional. You can use the software without an internet connection if you prefer.

## 💻 System requirements

- Operating System: Windows 10 or Windows 11.
- Memory: 4 gigabytes of RAM or higher.
- Storage: 100 megabytes of free space.
- Connectivity: An active internet connection helps if you choose to enable the optional synchronization features.

## 💡 Frequently asked questions

**Where does the application store my data?**
All data stays in a file on your local computer. This prevents unauthorized access from external services.

**Does the app run in the background?**
Yes. The app minimizes to the system tray. This keeps your main workspace clear while the service tracks your activity.

**How do I update the software?**
The application checks for updates when you launch it. If a new version exists, the app notifies you and offers a link to download the update.

**Can I export my data?**
Yes. Use the File menu in the dashboard to export your usage logs to a spreadsheet file. This allows you to perform custom analysis in other software.

**Is my data private?**
Your data stays entirely under your control. The application does not send your usage history or costs to any third party.

## 🛡 Security and privacy

This application follows a local-first approach. It does not require an account. You own the files on your machine. Because the application interacts with your local system, it does not need access to your personal web accounts or credit card information. 

The optional SSH sync feature uses encrypted tunnels to transfer data. This ensures that even when you sync across computers, your information remains protected from interception.

## 🤝 Getting help

If you encounter issues during installation or while the program runs, click the Help menu inside the dashboard. This menu provides links to common troubleshooting steps. If your problem persists, you can open a new issue on the GitHub repository page. Include a brief description of the problem and mention that you use the Windows version. This helps the developers solve your problem fast.

## 📜 License information

This project uses an open source license. You can view the full text of the license in the LICENSE file within the repository. The source code is available for your review if you have interest in the technical implementation. The code focuses on stability and minimal resource usage to ensure it adds no strain to your processor.