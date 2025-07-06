# Disable Google Chrome Auto-Update (Batch Script)

This repository contains a Windows batch script that helps you **disable Google Chrome's automatic updates** by deleting key update folders used by Google Update and GoogleUpdater.

---

## 🔧 What Does the Script Do?

- Automatically requests **Administrator privileges** (UAC prompt)
- Silently deletes chrome update files (if present)
- Prevents Chrome from silently reinstalling the update service

> ⚠️ Note: This script **does not disable** Chrome updates via registry or Group Policy. It only removes the components responsible for automatic updates. For more robust blocking, additional configuration may be needed.



## 🚀 How to Use

1. **Download** the `.zip` file from [HERE](https://github.com/seedtaha/disable-chrome-upadtes-forever-in-windows/releases)
2. Extract it.
3. Double-click the `.bat` file and allow to give **Administrator rights** when asks for.
4. Wait a second.
5. Done✅.

           <you can visit `chrome://settings/help` in Google Chrome so you can verify that the updates are disabled>

---

## ✅ Tested On

- Windows 10 (x64)
- Windows 11 (x64)
- Google Chrome (Enterprise & Standard installations)

---

## ⚠️ Disclaimer

This script is provided **as-is** for educational and administrative purposes. It may not work across all environments. Google Chrome may re-enable updates in future releases unless further blocked via registry or Group Policy.

---

## 📬 Contact

https://www.facebook.com/seed.103

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
