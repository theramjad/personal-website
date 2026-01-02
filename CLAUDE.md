# Project Guidelines

## Typography Style Guide

This documents the typography conventions used across the main personal pages (homepage, press, about).

### Page Structure

```tsx
<main className="min-h-screen bg-white dark:bg-neutral-800">
  <Navbar />
  <div className="max-w-2xl mx-auto px-6 pb-16">
    {/* Page content */}
  </div>
</main>
```

### Headings

- **h2 (Page title):** `text-2xl font-semibold mb-4 text-gray-900 dark:text-white`
- **h3 (Section heading):** `text-xl font-semibold mb-4 text-gray-900 dark:text-white`

### Body Text

- Standard paragraph: `text-gray-700 dark:text-gray-300 leading-relaxed mb-4`
- Last paragraph in section: `text-gray-700 dark:text-gray-300 leading-relaxed` (omit `mb-4`)

### Links

External links use:
```tsx
<a
  href="..."
  className="text-blue-600 dark:text-white hover:underline underline"
  target="_blank"
  rel="noopener noreferrer"
>
```

### Labels/Emphasis

- Inline labels: `<strong className="text-gray-900 dark:text-white">`
- Secondary/muted text: `text-gray-500 dark:text-gray-400`

### Lists

- Container spacing: `space-y-2`
- List item text: `text-gray-700 dark:text-gray-300`

### Color Reference

| Purpose | Light Mode | Dark Mode |
|---------|------------|-----------|
| Primary text | `text-gray-900` | `dark:text-white` |
| Body text | `text-gray-700` | `dark:text-gray-300` |
| Secondary text | `text-gray-500` | `dark:text-gray-400` |
| Links | `text-blue-600` | `dark:text-white` |
| Background | `bg-white` | `dark:bg-neutral-800` |
