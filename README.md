# 📱 Signal Registration Without Phone


<p align="center">
  <strong>Automate Signal CLI setup, installation, and configuration with ease!</strong>
</p>

<p align="center">
  <a href="#features">Features</a> •
  <a href="#prerequisites">Prerequisites</a> •
  <a href="#installation">Installation</a> •
  <a href="#usage">Usage</a> •
  <a href="#troubleshooting">Troubleshooting</a> •
  <a href="#contributing">Contributing</a> •
  <a href="#license">License</a>
</p>

## 🚀 Features

- **🔄 Automatic Download**: Fetches the latest Signal CLI version
- **☕ Java Setup**: Installs OpenJDK if needed
- **📞 Signal CLI Usage**: Guides through number registration and device linking
- **🎨 User-Friendly Interface**: Clear instructions with colorful console output

## 📋 Prerequisites

- Python 3.x
- Internet connection

## 💻 Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/signal-cli-setup.git
   cd signal-cli-setup
   ```

2. **Install required Python packages**:

   ```bash
   pip install -r requirements.txt
   ```

## 🔧 Usage

Run the script:

```bash
python register.py
```

Follow the on-screen prompts to:
1. 📥 Download and set up Signal CLI
2. 📝 Register your phone number
3. ✅ Verify your account
4. 🖥️ Add your Signal Desktop as a linked device

## 📚 Dependencies

- Built-in Python libraries: `os`, `subprocess`, `time`, `re`, `struct`, `tarfile`, `zipfile`
- External libraries:
  - `jdk`: Java operations
  - `requests`: HTTP requests
  - `github`: GitHub API interaction
  - `tqdm`: Progress bars
  - `PIL`: Image processing
  - `colorama`: Colored console output
  - `pyzbar`: QR code decoding

## 📝 Notes

- Ensure a stable internet connection throughout the setup
- Be prepared to solve a CAPTCHA during registration
- Use services like 5sim or sms-activate for verification codes
- Have a screenshot of the Signal Desktop QR code ready for linking

## 🔍 Troubleshooting

If you encounter issues:
- Verify all dependencies are correctly installed
- Check your internet connection
- Ensure you have necessary system permissions

For Windows users with `pyzbar` issues:
- Install [Microsoft Visual C++ Redistributable](https://www.microsoft.com/en-gb/download/details.aspx?id=40784)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! 
Feel free to check the [issues page](https://github.com/yourusername/signal-cli-setup/issues).

## 📄 License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/).