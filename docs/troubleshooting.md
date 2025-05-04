# 🧯 Troubleshooting Guide

Having issues running or developing the project? Here's a list of common problems and how to fix them.

---

## 🛠️ Common Issues & Fixes

### ❌ Error: `Module not found: Can't resolve 'xyz'`

**Cause:**  
Missing dependency or incorrect import path.

**Fix:**
```bash
# Reinstall packages
pnpm install

# Double check import path
```

---

### ❌ Error: `VITE_* is not defined`

**Cause:**  
Missing or incorrect `.env` setup.

**Fix:**
- Copy `.env.example` to `.env`
- Fill in the required variables
- Restart your dev server

---



> 📌 Tip: If you're often facing similar issues, consider updating this file with your solutions to help the team.
