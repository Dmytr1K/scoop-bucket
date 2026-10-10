# 🚀 Dmytr1K's Scoop Bucket

My personal third-party bucket (repository) for [Scoop](https://scoop.sh), containing custom manifests, useful utilities, and applications for Windows.

---

## 💻 How to add this bucket?

To add this bucket to your Scoop system, open your terminal (PowerShell) and run the following command:

```powershell
scoop bucket add dmytr1k https://github.com/Dmytr1K/scoop-bucket
```

## 📦 Installing Applications

Once the bucket is added, you can install applications from it by using the `dmytr1k/` prefix:

```powershell
scoop install dmytr1k/<app_name>
```

---

## 🔍 Available Applications

| Application | Description |
| :--- | :--- |
| `diffutils` | Cross-platform reimplementation of GNU diffutils |

---

## 🛠 Development & Adding Manifests

If you want to add a new manifest locally:

1. Create a new `.json` file inside the `bucket/` directory (you can use `bucket/app-name.json.template` as a starting point).
2. Test the manifest locally before committing:

   ```powershell
   scoop install .\bucket\app_name.json
   ```

3. Commit and push your changes to your GitHub repository.

---
🗋 License: [Unlicense](LICENSE)
