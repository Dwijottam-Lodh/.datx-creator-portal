# .datx-creator-portal
 A modular, encrypted, recursive JSON-based save/config file format with a built-in CLI editor and importer system. Replace .dat, .xml, .ini, .nbt and more — with .datx.
---------------------------------------------------------------------------------------------------------------------------------
# `.datx` Creator Portal

A terminal-based editor and manager for `.datx` files — a flexible, encrypted, modular, and importable JSON file format designed for:

- 🎮 Game saves & player data
- ⚙️ Configs & preferences
- 🧱 Modular world/chunk files
- 📦 Asset metadata
- 🌐 Multiplayer data sync

`.datx` is a modern replacement for outdated formats like `.dat`, `.xml`, `.ini`, `.nbt`, `.sav`, `.yaml`, and more.

---

## ✨ Features

- 🔐 XOR-based password encryption (user-defined length)
- 🧩 Nested file imports via `import:<filename.datx>`
- 📁 File-level immutability using OS read-only flags
- 🗜️ zlib compression & decompression support
- 🔍 Search for keys within `.datx` (supports nested dictionaries)
- 🛠️ Create, load, overwrite, and delete `.datx` files from a single CLI portal
- 🌐 JSON-native — works with any language or platform

---

## 📦 Use Cases

- Replace `.dat`, `.ini`, `.sav`, `.mca`, `.nbt` with one extensible format
- Encrypted game save systems
- Modular world chunks and player profiles
- Cross-platform multiplayer sync (e.g., `player_<uuid>.datx`)
- Web-compatible configs and settings
- Modder-safe editable files

---

## 🚀 Commands

| Command     | Description |
|-------------|-------------|
| `create`    | Create a new `.datx` file (optionally with nested imports) |
| `encrypt`   | Encrypt an existing plain `.datx` file |
| `decrypt`   | Decrypt an encrypted `.datx` file |
| `compress`  | Compress a `.datx` file with zlib |
| `decompress`| Decompress a zlib-compressed `.datx` |
| `load`      | View the content of a `.datx` file |
| `search`    | Find a key inside any `.datx` file |
| `overwrite` | Rewrite the entire contents of a `.datx` |
| `delete`    | Permanently delete a `.datx` file |
| `files`     | List all `.datx` files in current directory |
| `exit`      | Close the portal |

---

## 🧠 Philosophy

`.datx` was designed to bring sanity back to save and config files. Instead of juggling `.dat`, `.ini`, `.xml`, `.yaml`, and binary blobs, you now get:

- 🔄 Modularity
- 🔐 Optional encryption
- 📦 Compression
- 🔍 Easy inspection
- 🔧 Extensibility
- 🧠 Human and machine readability

---

## 📜 License

MIT — open, free to use, modify, and distribute.  
Just don’t claim it’s yours unless it actually is :D

---

## 👑 Author

Created by **Dwijottam Lodh** (aka the creator of the `.datx` format).  
If someone claims they made this first, just check the file timestamps. 📁⏳

---

## 🤝 Contributing

Want to improve the portal?  
Add AES encryption? A GUI? Versioning?  
Feel free to fork, PR, or file an issue. `.datx` is a format for builders.
---
This .datx format is a JSON-based modular encrypted file format general-purpose data storage. It is not related to the DSPCon .DATX binary telemetry format.
