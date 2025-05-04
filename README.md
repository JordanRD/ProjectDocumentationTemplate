# 🎯 MOSTrack - Frontend

A vehicle tracking website for customers.



## 🖥️ System Requirements

- OS: macOS, Linux, or Windows (WSL recommended on Windows)
- Node.js: >= 18.x.x
- Package Manager: pnpm (preferred) or npm

## 🔐 Environment Variables

To run this project locally, you'll need to set up a `.env` file at the root of the project.

.env Example :

```env
PORT=4444

# Auth
GOOGLE_MAPS_API_KEY={API_KEY}

# Endpoint
ENDPOINT_GRAPHQL=https://xyzcompany.com/graphql/v1
```


## ✨ Install Dependencies
Install dependencies
```bash
pnpm install
```
## ✨ Run the Project
Run the project
```bash
pnpm start 
```

## 📁 Project Structure

```
src/
├── components/      # Reusable UI components
├── pages/           # Route-based pages
├── hooks/           # Custom React hooks
├── assets/          # Static files like images, fonts
├── locales/         # i18n files
```


## 🧾 Code Standards & Naming Conventions
Check out [`docs/code-conventions`](./docs/code-conventions.md)

## 🐞 Common Issues
Check out [`docs/troubleshooting`](./docs/troubleshooting.md)