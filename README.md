# SECS Message Language (SML) for VS Code

Adds syntax highlighting for SECS Message Language (SML), commonly used in semiconductor equipment communication.

## ✨ Features

* Syntax highlighting for SECS message format
* Highlights:
  * **Type** keywords (`L`, `A`, `B`, `U1`, `F8`, etc.)
  * **Count** indicators (e.g., `[2]`, optional)
  * **Values** — numbers, hex, strings
* Supports nested data blocks with angle brackets `<...>`

![Syntax Highlighting Example](images/preview.png)

## 📦 File Support

* Automatically activates for `.sml` files
* Language ID: `sml`

## 🧹 Requirements

No dependencies. Works out of the box with VS Code **1.102.0** or later.

## ⚠️ Known Issues

* Code folding and auto indentation not implemented
* No syntax validation or intellisense (highlighting only)

## 📜 Release Notes

### 0.0.1

* Initial release with basic syntax highlighting support

---

**Enjoy working with SML in VS Code!**

For feedback or feature requests, please open an issue on GitHub.
