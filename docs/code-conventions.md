
# 🧾 Code Conventions

Consistency is key in a growing codebase. These standards make our frontend project easier to read, maintain, and scale — especially when working in teams.

## 📦 File & Folder Naming

| Type             | Convention   | ✅ Do                      | ❌ Don't                     |
|------------------|--------------|----------------------------|------------------------------|
| CSS files        | kebab-case   | `user-card.module.css`     | `UserCard.module.css`        |
| Asset folders    | kebab-case   | `profile-images/`          | `ProfileImages/`             |
| Component files  | PascalCase   | `LoginForm.tsx`            | `loginform.tsx`, `login.tsx` |
| Hook files       | camelCase    | `useAuth.ts`               | `authHook.ts`                |

---

## 🔠 Naming Rules by Type

### 🔤 Classes & Components

- Use **PascalCase**
- Components should be named by *what they are*, not how they look

```tsx
// ✅ Do
class UserService {}
function UserCard() {}

// ❌ Don't
class userService {}
function cardBlue() {}
```

---

### 🔧 Functions & Hooks

- Use **camelCase**
- Hooks **must** start with `use`
- Name functions with clear **verbs** that describe action
- Use **arrow functions**, except for components or page-level functions

```ts
// ✅ Do
const fetchUserData = () => {}
const useUserForm = () => {}
function Dashboard() {}

// ❌ Don't
function dataFetch() {}
const hookUser = () => {}
const Dashboard = () => {}
```

---

### 📌 Constants

- Use **UPPER_SNAKE_CASE**

```ts
// ✅ Do
const API_URL = 'https://example.com'

// ❌ Don't
const apiUrl = 'https://example.com'
```

---

### 📊 Variables

- Use **camelCase**
- Boolean variables should start with `is`, `has`, or `can`

```ts
// ✅ Do
const isLoggedIn = true
const userProfile = {}

// ❌ Don't
const logged = true
const User_profile = {}
```

---

### ⚠️ General Naming Rules

| Rule | ✅ Do | ❌ Don't |
|------|------|----------|
| Use meaningful, consistent names | `userProfile`, `fetchUserData()` | `uData`, `loadInfo()` |
| Avoid multiple names for same concept | Use `button` everywhere | Mixing `btn`, `button`, `action` |
| Avoid same name for different things | `getUser()` for user fetching only | `getUser()` for both fetching and caching |
| No abbreviations unless widely known | `API`, `URL` | `usr`, `cfg`, `prf` |

---

## 🔁 Variable Declarations

- Always use `const` or `let` (never `var`)
- Default to `const` unless reassignment is needed

```ts
// ✅ Do
const token = 'abc123'
let counter = 0

// ❌ Don't
var name = 'John'
```

---

## 🧪 Summary Cheat Sheet

| Type             | Convention       |
|------------------|------------------|
| Class / Component| `PascalCase`     |
| Function         | `camelCase`, with verb |
| Hook             | `camelCase`, starts with `use` |
| Constant         | `UPPER_SNAKE_CASE` |
| Variable         | `camelCase`, use `is`, `has`, `can` for booleans |
| CSS / Assets     | `kebab-case`     |

---

> Let consistency do the talking, not the person who last touched the code.
