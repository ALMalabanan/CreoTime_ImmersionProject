# Creo-Time ⏰

> A simple and secure employee time tracking mobile application built with MIT App Inventor

![Platform](https://img.shields.io/badge/platform-Android-green.svg)
![MIT App Inventor](https://img.shields.io/badge/built%20with-MIT%20App%20Inventor-orange.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

## 📋 Table of Contents

- [About](#-about)
- [Demo](#-demo)
- [Features](#-features)
- [Built With](#-built-with)
- [Installation](#-installation)
- [Usage](#-usage)
- [Repository Contents](#-repository-contents)
- [How to Import Project](#-how-to-import-project)
- [Known Limitations](#-known-limitations)
- [Future Improvements](#-future-improvements)
- [Credits](#-credits)


## 📖 About 

Creo-Time is an employee time tracking mobile application developed using **MIT App Inventor**. It provides a fast, easy-to-use, and secure solution for recording employee working hours and managing daily time records. 

This application was specifically developed to help **CREOTEC Philippines Inc.** monitor and record employee time-in and time-out data as an alternative to traditional paper-based daily time recording systems.

**Who is it for?**
- Small businesses transitioning from manual time tracking
- Companies looking for simple digital attendance solutions
- Organizations needing basic employee time monitoring
- Educational institutions teaching mobile app development

**Why is it useful?**
- Eliminates paper-based attendance systems
- Provides easy access to time records
- Simple interface suitable for all age groups
- Cost-effective solution built with visual programming

## 🎬 Demo

### Screenshots
*Screenshots will be added once available*

### APK Download
The compiled Android application (.apk file) is available in this repository for direct installation on Android devices.

> **Note:** This app is built for Android devices and requires Android 4.1 (API level 16) or higher.

## ✨ Features

Based on the application documentation, Creo-Time includes:

- **👤 Create Personal Profile**: Users can set up and manage their own employee profiles
- **⏱️ Time In/Out Recording**: Simple interface to record arrival and departure times
- **📊 Daily Time Record**: View and track daily working hours and attendance patterns
- **🔒 Secure Data Storage**: Local data storage with privacy protection
- **📱 Mobile-Optimized**: Designed specifically for Android mobile devices
- **🎯 Essential Information Focus**: Clean interface showing only the most important time tracking data

## 🛠️ Built With

**Development Platform:**
- [MIT App Inventor](http://appinventor.mit.edu/) - Visual programming platform for mobile apps

**Target Platform:**
- Android (APK compilation)
- Minimum Android API Level 16+

**Development Approach:**
- Visual block-based programming
- Drag-and-drop interface design
- No traditional coding required

**Data Storage:**
- Local device storage (TinyDB component)
- No external database required

## 📱 Installation

### For End Users (APK Installation)

1. **Download APK**
   ```
   Download the Creo-Time.apk file from this repository
   ```

2. **Enable Unknown Sources**
   - Go to Android Settings → Security
   - Enable "Unknown sources" or "Install unknown apps"
   
3. **Install Application**
   - Locate the downloaded APK file
   - Tap to install
   - Follow installation prompts

### For Developers (MIT App Inventor)

1. **Access MIT App Inventor**
   - Visit [http://appinventor.mit.edu/](http://appinventor.mit.edu/)
   - Sign in with your Google account

2. **Import Project**
   - Click "Projects" → "Import project (.aia) from my computer"
   - Select the `Creo-Time.aia` file from this repository
   - Wait for import to complete

## 📖 Usage

### Getting Started

1. **Install the App**
   - Install the APK file on your Android device
   - Launch the Creo-Time application

2. **Create Your Profile**
   - Open the app for the first time
   - Set up your employee profile with required information

3. **Daily Time Tracking**
   - Use the "Time In" feature when starting work
   - Use "Time Out" feature when ending work
   - View your daily time records in the app

### Basic Workflow

**Daily Operations:**
- Open Creo-Time app
- Record time in at start of workday
- Record time out at end of workday
- Review daily time record summary

**Profile Management:**
- Access profile settings within the app
- Update personal information as needed
- View historical time records

## 📁 Repository Contents

```
creo-time/
├── Creo-Time.apk              # Compiled Android application
├── Creo-Time.aia             # MIT App Inventor project file
├── About and privacy.pdf     # App information and privacy policy
├── About this app(Creo-Time).pdf  # Application description
├── CREOTIME User's Guide.pdf # User manual and instructions
├── README.md                 # This documentation file
└── LICENSE                   # License information
```
## 🔄 How to Import Project

### For MIT App Inventor Developers

1. **Download Project File**
   ```
   Download the Creo-Time.aia file from this repository
   ```

2. **Import to MIT App Inventor**
   - Log into MIT App Inventor
   - Go to "Projects" menu
   - Select "Import project (.aia) from my computer"
   - Choose the downloaded .aia file
   - Click "OK" to import

3. **Modify and Customize**
   - Edit blocks and design as needed
   - Test using the MIT App Inventor emulator or AI Companion
   - Build new APK when ready to deploy

## ⚠️ Known Limitations

**MIT App Inventor Constraints:**
- Android-only platform (no iOS version)
- Limited to MIT App Inventor's built-in components
- Local storage only (no cloud sync)
- Basic UI design options
- No advanced authentication systems

**Application-Specific:**
- Requires manual time entry (no automatic GPS tracking)
- Data stored locally on device only
- Limited reporting capabilities
- No multi-user management system
- Basic export options

  ## 🔮 Future Improvements

### Possible Enhancements (within MIT App Inventor)
- [ ] Add reminder notifications using Notifier component
- [ ] Implement data backup to Google Sheets
- [ ] Add photo capture for time entries using Camera component
- [ ] Include location services using LocationSensor
- [ ] Add email export functionality using ActivityStarter

### Advanced Features (requiring migration)
- [ ] Cloud database integration
- [ ] Multi-platform support (iOS)
- [ ] Advanced reporting dashboard
- [ ] Manager approval workflows
- [ ] Payroll system integration

## 🔐 Privacy & Security

Based on the privacy policy included in this repository:

**Data Collection:**
- Personal information collected only for app functionality
- Data used for providing and improving the service
- No sharing with third parties except as described in privacy policy

**Cookies:**
- App uses cookies for service improvement
- Users can choose to accept or refuse cookies
- Some features may be limited if cookies are refused

**Security:**
- Commercially acceptable means used to protect personal information
- No method of transmission is 100% secure
- Local device storage provides additional privacy protection

## 🙏 Credits

### Development
- **Batch 1 Work Immersion** - Original concept, development, and implementation
- **MIT App Inventor** - Development platform and tools

### Documentation
- Application documentation and user guides
- Privacy policy and terms of service
- Technical specifications

### Platform
- MIT Massachusetts Institute of Technology - App Inventor platform
- Google - Android platform support
