# Scaffolded – TypeScript & React Snippets

Opinionated **TypeScript & React snippets** for developers who want clean structure, predictable layouts, and less boilerplate.

Scaffolded focuses on **component scaffolding**, **modern React hooks**, and **state / GraphQL templates**, all organised with clear sections so your files stay readable as they grow.

---

## ✨ Features

- 🧱 Structured React component scaffolds
- ⚛️ Modern React hooks (`useCallback`, `useMemo`)
- 🗂 Clear sectioned layouts (MAIN / HOOKS / EXPORTS / REGIONS)
- 🧠 Zustand store templates with strong typing
- 🔌 React Context boilerplate
- 🔗 GraphQL query & mutation templates
- 🧪 Lightweight, zero-runtime extension (snippets only)

---

## 📦 Included Snippets

### TypeScript

| Prefix | Description |
|------|------------|
| `scaf` | Type scaffold with exports |
| `zs` | Zustand store with typed state |

---

### TypeScript React

#### Component scaffolding

| Prefix | Description |
|------|------------|
| `monoScaf` | Single-file component scaffold |
| `scaf` | React functional component scaffold (split props) |
| `scafR` | Component scaffold with `#region` sections |
| `ctx` | React Context + Provider + hook |

#### Hooks & utilities

| Prefix | Description |
|------|------------|
| `ucb` | `useCallback` template |
| `umm` | `useMemo` template |
| `clg` | `console.log()` |

#### Tags

| Prefix | Description |
|------|------------|
| `t1` | Main TSX tag for big sections like MAIN, EXPORTS |
| `t2` | Secondary TSX tag for sections like HOOKS, APIs, VARIABLES, EVENTS, RENDERER, VIEWS |
| `t2R` | Secondary TSX region tag (begin/end) for sections like HOOKS, APIs, VARIABLES, EVENTS, RENDERER, VIEWS |

#### GraphQL

| Prefix | Description |
|------|------------|
| `g` | GraphQL query template |
| `gqp` | GraphQL paginated query template |
| `gm` | GraphQL mutation template |

---

## 🧩 Example

Type `scaf` in a `.tsx` file:

```tsx
const MyComponentView = (props: MyComponentProps) => {
  // =============== HOOKS

  // =============== APIs

  // =============== VARIABLES

  // =============== EVENTS

  // =============== VIEWS
  return <></>;
};

```

---

## 📄 License

MIT © 2026 Joe Lau
