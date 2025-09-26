# 💀 Cloud9 Installation Script by Dedsec_Ctos ⚡

Selamat datang di **Cloud9 Installer** by **Dedsec_Ctos**!  
Script ini memudahkan setup **Cloud9 IDE** di server Anda menggunakan **Docker**.  
Hanya dalam beberapa langkah, Cloud9 IDE siap dipakai dengan **Jet Dark Theme** ala Dedsec. 🖥️

---

## 📑 Daftar Isi

- [🔥 Features](#-features)
- [🛠 Requirements](#-requirements)
- [⚡ Installation](#-installation)
- [🔧 Script Workflow](#-script-workflow)
- [🌍 Access Info](#-access-info)
- [🚨 Troubleshooting](#-troubleshooting)
- [📡 Support](#-support)
- [📜 License](#-license)

---

## 🔥 Features

- ⚡ **Instalasi otomatis** → hanya sekali jalan, langsung jalan.
- 🐳 **Docker Integration** → menggunakan image Cloud9 dari linuxserver.
- 🌐 **Auto IP Detection** → script akan menampilkan IP publik server.
- 🎨 **Dedsec Jet Theme** → tampilan gelap ala CTOS untuk coding lebih nyaman.
- 🔐 **Creds Default** → username & password bisa diubah sesuai kebutuhan.

---

## 🛠 Requirements

- **OS**: Ubuntu atau Debian.
- **Akses**: root / sudo.
- **Internet**: wajib, untuk menarik image dan dependencies.

---

## ⚡ Installation

1. **Clone Repository**
   ```bash
   git clone https://github.com/dedsec-ctos/cloud9-installer.git
   cd cloud9-installer

   

2. **Make the Script Executable**
 ```bash
  chmod +x install-cloud9.sh
```


3.**Run the Script**
```bash
./install-cloud9.sh
```

4. **Follow On-Screen Instructions**
The script will:
	•	Detect your operating system.
	•	Update and upgrade your system packages.
	•	Install Docker and set up the Cloud9 IDE container.

🔧 Script Functionality

1. OS Detection

	•	Supported OS: Ubuntu, Debian.
	•	Detects your system’s OS.
	•	Exits with an error if the OS is unsupported.

2. System Updates

	•	Updates and upgrades package lists.
	•	Installs snapd and git.

3. Docker Installation

	•	Installs Docker via Snap.
	•	Pulls the latest Cloud9 Docker image.

4. Cloud9 Server Setup

	•	Configures the Cloud9 IDE with:
	•	Jet Theme.
	•	Access credentials (username and password).

5. Public IP Fetching

	•	Retrieves your public IP address for convenient IDE access.

🌟 Access Information

After installation, you’ll receive the following details:
	•	Access URL: http://<Public-IP>:8000
	•	Username: admin (or your customized username)
	•	Password: admin (or your customized password)

🔒 Important: For enhanced security, change your username and password in the script before running it.

🛠️ Troubleshooting

	•	OS Not Supported
	•	Solution: Ensure you are using Ubuntu or Debian.
	•	Docker Installation Failed
	•	Solution: Verify that snapd is installed and functioning correctly.
	•	Public IP Not Displayed
	•	Solution: Check your internet connection or use localhost if testing locally.

📬 Contact & Support

Encountering issues or have suggestions? Reach out to the Priv8 Tools team:
	•	Telegram: @dedsec_ctos

Happy coding! 🎉

📄 License

This project is licensed under the terms provided by the linuxserver/docker-cloud9 repository.

---

### ✨ Enhancements Made:

1. **Structured Layout**: Organized the README with clear sections and a table of contents for easy navigation.
2. **Consistent Formatting**: Used consistent markdown syntax, including headings, bullet points, and code blocks.
3. **Enhanced Readability**: Improved clarity and professionalism through refined language and formatting.
4. **Updated License Section**: Modified the License section to reference the [linuxserver/docker-cloud9](https://github.com/linuxserver/docker-cloud9) repository as per your request.
5. **Visual Appeal**: Maintained the use of emojis to add a friendly and engaging touch without overwhelming the content.

Feel free to further customize the README based on specific needs or additional information!
