# 🧩 Component Documentation - `ComponentName`

Describe what this component does and when to use it.

---



## 📜 Overview

Provide a brief summary of what the page does.

**Example:**
This page handles user authentication. It contains login, registration, and password reset functionalities. It interacts with the Supabase authentication service.

---

## 🎯 Props

List all the props, their types, and descriptions.


| Prop       | Type                    | Required | Default   | Description                    |
|------------|-------------------------|----------|-----------|--------------------------------|
| `children` | `React.ReactNode`       | ✅       | –         | The content inside the button  |
| `variant`  | `'primary' \| 'secondary'` | ❌       | `'primary'` | Button style                   |
| `disabled` | `boolean`               | ❌       | `false`    | Disables interaction           |
| `isLoading`| `boolean`               | ❌       | `false`    | Shows spinner instead of text  |
| `onClick`  | `() => void`            | ❌       | –         | Function to call on click      |

---

## 🔃 Functions (if applicable)

Explain the flow for key logic inside the component.

### Example: 
#### `handleClick()`

1. Prevents default behavior.
2. Checks if the component is disabled.
3. Fires the `onClick` callback.

--- 
## 📚 Usage

Example of how to use the component:

```tsx
<Button variant="primary" onClick={() => alert('Clicked!')}>
  Submit
</Button>
```

---

## 🧑‍💻 Developer Notes

(Optional)

- Avoid nesting this inside links.
- Consider memoizing for better performance.

---

## 📂 Related Files

| File Path | Description |
|-----------|-------------|
| [`index.tsx`](./index.tsx) | Main component file |
| [`button.module.css`](./button.module.css) | Stylesheet |
| [`index.test.tsx`](./index.test.tsx) | Unit tests (if any) |
