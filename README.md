# MAS-Scripts

A collection of utility scripts for **Microsoft Activation Scripts (MAS)** - streamlining Windows and Office activation through automated PowerShell and batch scripts.

## 📋 Overview

MAS-Scripts provides a comprehensive toolkit for activating Microsoft Windows and Office products using legitimate activation methods. These scripts automate the activation process, making it simple and efficient for users who need to manage multiple installations or prefer command-line tools.

## ✨ Features

- **Windows Activation**: Automated scripts for activating various Windows versions
- **Office Activation**: Support for Microsoft Office suite activation
- **Multiple Methods**: Includes KMS, HWID, and other activation techniques
- **Easy to Use**: Simple command-line interface with minimal user input required
- **Batch Processing**: Automate activation across multiple systems
- **Error Handling**: Built-in validation and error reporting

## 🚀 Getting Started

### Prerequisites

- Windows operating system (Windows 7 or later)
- Administrator privileges
- PowerShell 5.1 or later
- Internet connection (for some activation methods)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/aryann-7/MAS-Scripts.git
```

2. Navigate to the project directory:
```bash
cd MAS-Scripts
```

3. Run scripts with administrator privileges

## 📖 Usage

### Basic Activation

1. **Right-click** on the desired script
2. Select **"Run as Administrator"**
3. Follow the on-screen prompts
4. Wait for the activation process to complete

### Command Line Usage

```powershell
# For Windows activation
.\ActivateWindows.cmd

# For Office activation
.\ActivateOffice.cmd
```

## 🛠️ Script Descriptions

### Windows Activation Scripts
- **HWID Activation**: Hardware-based permanent activation
- **KMS38 Activation**: Valid until 2038
- **Online KMS**: Requires internet connection

### Office Activation Scripts
- **Office Retail to Volume**: Convert retail to volume license
- **Office KMS Activation**: Network-based activation

## ⚠️ Important Notes

- Always run scripts with **administrator privileges**
- Some antivirus software may flag these scripts as potentially unwanted programs (PUP) - this is a false positive due to the nature of activation scripts
- These scripts are intended for **educational and testing purposes**
- Ensure you have legitimate licenses for the software you're activating
- Create a system restore point before running any activation scripts

## 🔧 Troubleshooting

### Common Issues

**Script won't run:**
- Ensure you're running as Administrator
- Check PowerShell execution policy: `Set-ExecutionPolicy Bypass -Scope Process`

**Activation fails:**
- Verify internet connection
- Disable antivirus temporarily
- Check Windows/Office version compatibility

**Error messages:**
- Review the script output for specific error codes
- Ensure Windows Update service is running
- Check if product is already activated

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is provided as-is for educational purposes. Users are responsible for ensuring they comply with Microsoft's licensing terms and applicable laws in their jurisdiction.

## 🔗 Related Resources

- [Microsoft Activation Scripts Official](https://massgrave.dev/)
- [Microsoft Volume Licensing](https://www.microsoft.com/licensing)
- [Windows Activation Documentation](https://docs.microsoft.com/windows/deployment/volume-activation)

## 👨‍💻 Author

**Aryann**
- GitHub: [@aryann-7](https://github.com/aryann-7)

## 📞 Support

If you encounter any issues or have questions:
- Open an issue on GitHub
- Check the troubleshooting section above
- Review existing issues for solutions

## ⭐ Show Your Support

If you found this project helpful, please consider giving it a star on GitHub!

---

**Disclaimer**: This repository is for educational purposes only. Users must ensure they have proper licensing for any Microsoft products they activate. The author is not responsible for any misuse of these scripts.
