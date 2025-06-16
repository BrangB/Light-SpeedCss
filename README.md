# @brang/light-speedcss

A lightning-fast, utility-first CSS framework for building modern, responsive, and beautiful user interfaces with minimal effort.

## 🚀 Features

- 🎨 Utility-first classes for layout, typography, spacing, and more  
- ⚡ Lightweight and performance-focused  
- 🧩 Easily customizable with theming support  
- 📱 Responsive design baked in  
- 🌘 Dark mode ready

## 📦 Installation

```sh
npm install light-speedcss
```

## 🔧 Usage
Use By Linking the files from node_modules:
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@brang/light-speedcss@latest/dist/light-speed.css" />
```

```html
<div class="text-center bg-primary text-white p-4 rounded">
  Welcome to Light-SpeedCSS 🚀
</div>
```

## 🎨 Text Color Utilities
Apply semantic, theme-aware text colors using utility classes. Colors are mapped to CSS variables for easy theming.

### 🔴 Red
```css
.text-red-100 → var(--color-red-100)
.... 
.text-red-500 → var(--color-red-500)  
.text-red-900 → var(--color-red-800)
```

### 🔵 Blue
```css
.text-blue-100 → var(--color-blue-100)  
.text-blue-500 → var(--color-blue-500)  
.text-blue-800 → var(--color-blue-800)
```

## 🎨 Red Color Scale

## 🔵 Red

| Token              | Color     |
|--------------------|-----------|
| `--color-red-50`   | `#fef2f2` |
| `--color-red-100`  | `#fee2e2` |
| `--color-red-200`  | `#fecaca` |
| `--color-red-300`  | `#fca5a5` |
| `--color-red-400`  | `#f87171` |
| `--color-red-500`  | `#ef4444` |
| `--color-red-600`  | `#dc2626` |
| `--color-red-700`  | `#b91c1c` |
| `--color-red-800`  | `#991b1b` |
| `--color-red-900`  | `#7f1d1d` |

---

## 🔵 Blue

| Token              | Color     |
|--------------------|-----------|
| `--color-blue-100` | `#bfdbfe` |
| `--color-blue-200` | `#93c5fd` |
| `--color-blue-300` | `#60a5fa` |
| `--color-blue-400` | `#3b82f6` |
| `--color-blue-500` | `#2563eb` |
| `--color-blue-600` | `#1d4ed8` |
| `--color-blue-700` | `#1e40af` |
| `--color-blue-800` | `#1e3a8a` |

---

## 🟢 Green

| Token               | Color     |
|---------------------|-----------|
| `--color-green-50`  | `#d1fae5` |
| `--color-green-100` | `#a7f3d0` |
| `--color-green-200` | `#6ee7b7` |
| `--color-green-300` | `#34d399` |
| `--color-green-400` | `#10b981` |
| `--color-green-500` | `#059669` |
| `--color-green-600` | `#047857` |
| `--color-green-700` | `#065f46` |
| `--color-green-800` | `#064e3b` |

---

## ⚪ Gray

| Token              | Color     |
|--------------------|-----------|
| `--color-gray-50`  | `#f3f4f6` |
| `--color-gray-100` | `#e5e7eb` |
| `--color-gray-200` | `#d1d5db` |
| `--color-gray-300` | `#9ca3af` |
| `--color-gray-400` | `#6b7280` |
| `--color-gray-500` | `#4b5563` |
| `--color-gray-600` | `#374151` |
| `--color-gray-700` | `#1f2937` |
| `--color-gray-800` | `#111827` |

---

## 🟡 Yellow

| Token                | Color     |
|----------------------|-----------|
| `--color-yellow-50`  | `#fef9c3` |
| `--color-yellow-100` | `#fef08a` |
| `--color-yellow-200` | `#fde047` |
| `--color-yellow-300` | `#facc15` |
| `--color-yellow-400` | `#eab308` |
| `--color-yellow-500` | `#ca8a04` |
| `--color-yellow-600` | `#a16207` |
| `--color-yellow-700` | `#854d0e` |
| `--color-yellow-800` | `#713f12` |

---

## 🟦 Indigo

| Token               | Color     |
|---------------------|-----------|
| `--color-indigo-50`  | `#e0e7ff` |
| `--color-indigo-100` | `#c7d2fe` |
| `--color-indigo-200` | `#a5b4fc` |
| `--color-indigo-300` | `#818cf8` |
| `--color-indigo-400` | `#6366f1` |
| `--color-indigo-500` | `#4f46e5` |
| `--color-indigo-600` | `#4338ca` |
| `--color-indigo-700` | `#3730a3` |
| `--color-indigo-800` | `#312e81` |

---

## 🟪 Purple

| Token               | Color     |
|---------------------|-----------|
| `--color-purple-50`  | `#f3e8ff` |
| `--color-purple-100` | `#e9d5ff` |
| `--color-purple-200` | `#d8b4fe` |
| `--color-purple-300` | `#c084fc` |
| `--color-purple-400` | `#a855f7` |
| `--color-purple-500` | `#9333ea` |
| `--color-purple-600` | `#7e22ce` |
| `--color-purple-700` | `#6b21a8` |
| `--color-purple-800` | `#581c87` |

---

## 🌸 Pink

| Token              | Color     |
|--------------------|-----------|
| `--color-pink-50`  | `#fce7f3` |
| `--color-pink-100` | `#fbcfe8` |
| `--color-pink-200` | `#f9a8d4` |
| `--color-pink-300` | `#f472b6` |
| `--color-pink-400` | `#ec4899` |
| `--color-pink-500` | `#db2777` |
| `--color-pink-600` | `#be185d` |
| `--color-pink-700` | `#9d174d` |
| `--color-pink-800` | `#831843` |

---

## 🧡 Orange

| Token               | Color     |
|---------------------|-----------|
| `--color-orange-50`  | `#ffedd5` |
| `--color-orange-100` | `#fed7aa` |
| `--color-orange-200` | `#fdba74` |
| `--color-orange-300` | `#fb923c` |
| `--color-orange-400` | `#f97316` |
| `--color-orange-500` | `#ea580c` |
| `--color-orange-600` | `#c2410c` |
| `--color-orange-700` | `#9a3412` |
| `--color-orange-800` | `#7c2d12` |

---

## 🟦 Teal

| Token              | Color     |
|--------------------|-----------|
| `--color-teal-50`  | `#ccfbf1` |
| `--color-teal-100` | `#99f6e4` |
| `--color-teal-200` | `#5eead4` |
| `--color-teal-300` | `#2dd4bf` |
| `--color-teal-400` | `#14b8a6` |
| `--color-teal-500` | `#0d9488` |
| `--color-teal-600` | `#0f766e` |
| `--color-teal-700` | `#115e59` |
| `--color-teal-800` | `#134e4a` |

---

## 💎 Cyan

| Token              | Color     |
|--------------------|-----------|
| `--color-cyan-50`  | `#cffafe` |
| `--color-cyan-100` | `#a5f3fc` |
| `--color-cyan-200` | `#67e8f9` |
| `--color-cyan-300` | `#22d3ee` |
| `--color-cyan-400` | `#06b6d4` |
| `--color-cyan-500` | `#0891b2` |
| `--color-cyan-600` | `#0e7490` |
| `--color-cyan-700` | `#155e75` |
| `--color-cyan-800` | `#164e63` |

---

## 💚 Lime

| Token              | Color     |
|--------------------|-----------|
| `--color-lime-50`  | `#ecfccb` |
| `--color-lime-100` | `#d9f99d` |
| `--color-lime-200` | `#bef264` |
| `--color-lime-300` | `#a3e635` |
| `--color-lime-400` | `#84cc16` |
| `--color-lime-500` | `#65a30d` |
| `--color-lime-600` | `#4d7c0f` |
| `--color-lime-700` | `#3f6212` |
| `--color-lime-800` | `#365314` |

---

## 🟠 Amber

| Token               | Color     |
|---------------------|-----------|
| `--color-amber-50`  | `#fef3c7` |
| `--color-amber-100` | `#fde68a` |
| `--color-amber-200` | `#fcd34d` |
| `--color-amber-300` | `#fbbf24` |
| `--color-amber-400` | `#f59e0b` |
| `--color-amber-500` | `#d97706` |
| `--color-amber-600` | `#b45309` |
| `--color-amber-700` | `#92400e` |
| `--color-amber-800` | `#78350f` |

---

## 🌤 Sky

| Token             | Color     |
|-------------------|-----------|
| `--color-sky-50`  | `#e0f2fe` |
| `--color-sky-100` | `#bae6fd` |
| `--color-sky-200` | `#7dd3fc` |
| `--color-sky-300` | `#38bdf8` |
| `--color-sky-400` | `#0ea5e9` |
| `--color-sky-500` | `#0284c7` |
| `--color-sky-600` | `#0369a1` |
| `--color-sky-700` | `#075985` |
| `--color-sky-800` | `#0c4a6e` |

---

## 💜 Violet

| Token                | Color     |
|----------------------|-----------|
| `--color-violet-50`  | `#ede9fe` |
| `--color-violet-100` | `#ddd6fe` |
| `--color-violet-200` | `#c4b5fd` |
| `--color-violet-300` | `#a78bfa` |
| `--color-violet-400` | `#8b5cf6` |
| `--color-violet-500` | `#7c3aed` |
| `--color-violet-600` | `#6d28d9` |
| `--color-violet-700` | `#5b21b6` |
| `--color-violet-800` | `#4c1d95` |

---

## 🌸 Fuchsia

| Token                 | Color     |
|-----------------------|-----------|
| `--color-fuchsia-50`  | `#fae8ff` |
| `--color-fuchsia-100` | `#f5d0fe` |
| `--color-fuchsia-200` | `#f0abfc` |
| `--color-fuchsia-300` | `#e879f9` |
| `--color-fuchsia-400` | `#d946ef` |
| `--color-fuchsia-500` | `#c026d3` |
| `--color-fuchsia-600` | `#a21caf` |
| `--color-fuchsia-700` | `#86198f` |
| `--color-fuchsia-800` | `#701a75` |

---

## 🌹 Rose

| Token              | Color     |
|--------------------|-----------|
| `--color-rose-50`  | `#ffe4e6` |
| `--color-rose-100` | `#fecdd3` |
| `--color-rose-200` | `#fda4af` |
| `--color-rose-300` | `#fb7185` |
| `--color-rose-400` | `#f43f5e` |
| `--color-rose-500` | `#e11d48` |
| `--color-rose-600` | `#be123c` |
| `--color-rose-700` | `#9f1239` |
| `--color-rose-800` | `#881337` |



## ✍️ Typography Utilities

### 🅰️ Font Sizes

Control text size using semantic utility classes:

| Class         | Size     | Description            |
|---------------|----------|------------------------|
| `.text-xs`    | 0.75rem  | Extra small            |
| `.text-sm`    | 0.875rem | Small                  |
| `.text-base`  | 1rem     | Default size           |
| `.text-lg`    | 1.125rem | Large                  |
| `.text-xl`    | 1.25rem  | Extra large            |
| `.text-2xl`   | 1.5rem   | 2× large               |
| `.text-3xl`   | 1.875rem | 3× large               |
| `.text-4xl`   | 2.25rem  | 4× large               |

### 💪 Font Weights

Easily adjust font weight for emphasis or subtlety:

| Class             | Weight |
|------------------|--------|
| `.font-thin`      | 100    |
| `.font-light`     | 300    |
| `.font-normal`    | 400    |
| `.font-medium`    | 500    |
| `.font-semibold`  | 600    |
| `.font-bold`      | 700    |
| `.font-extrabold` | 800    |



## 📏 Spacing Utilities

Control layout spacing using margin, padding, and gap utilities.

### 🔲 Margin & Padding Scale

| Class | rem | px  |
|-------|-----|-----|
| `*-0`   | 0   | 0   |
| `*-1`   | 0.25rem | 4px |
| `*-2`   | 0.5rem  | 8px |
| `*-3`   | 1rem    | 16px |
| `*-4`   | 1.5rem  | 24px |
| `*-5`   | 2rem    | 32px |
| `*-6`   | 2.5rem  | 40px |
| `*-8`   | 3rem    | 48px |
| `*-10`  | 4rem    | 64px |

### ↔️ Margin

- `.m-*` – All sides  
- `.mx-*` – Horizontal (left + right)  
- `.my-*` – Vertical (top + bottom)  
- `.mt-*`, `.mr-*`, `.mb-*`, `.ml-*` – Individual sides

### 📦 Padding

- `.p-*` – All sides  
- `.px-*` – Horizontal  
- `.py-*` – Vertical  
- `.pt-*`, `.pr-*`, `.pb-*`, `.pl-*` – Individual sides

### 🔳 Gap (Flex & Grid)

- `.gap-*` – Sets gap between items  
- `.row-gap-*` – Vertical gaps only  
- `.col-gap-*` – Horizontal gaps only

### 🧪 Example

```html
<div class="p-4 mb-6">
  <div class="gap-4 flex">
    <div class="p-2 bg-gray-200">Box 1</div>
    <div class="p-2 bg-gray-300">Box 2</div>
  </div>
</div>
```

## 🧱 Z-Index Utilities

Control stacking order with predictable, consistent values.

| Class       | Value          |
|-------------|----------------|
| `.z-0`      | `z-index: 0`   |
| `.z-10`     | `z-index: 10`  |
| `.z-20`     | `z-index: 20`  |
| `.z-30`     | `z-index: 30`  |
| `.z-40`     | `z-index: 40`  |
| `.z-50`     | `z-index: 50`  |
| `.z-auto`   | `z-index: auto`|

---


## 🔧 Flexbox Utilities

Easily create responsive and adaptive layouts using Flexbox utility classes.

## 🖼 Display Utilities

Quickly control how elements are displayed.

| Class             | Value               |
|-------------------|---------------------|
| `.d-block`        | `display: block`     |
| `.d-inline`       | `display: inline`    |
| `.d-inline-block` | `display: inline-block` |
| `.d-flex`         | `display: flex`      |
| `.d-inline-flex`  | `display: inline-flex` |
| `.d-grid`         | `display: grid`      |
| `.d-inline-grid`  | `display: inline-grid` |
| `.d-none`         | `display: none`      |

### ↕ Flex Direction

| Class               | Description              |
|---------------------|--------------------------|
| `.flex-row`         | `flex-direction: row`    |
| `.flex-col`         | `flex-direction: column` |
| `.flex-row-reverse` | `row` in reverse order   |
| `.flex-col-reverse` | `column` in reverse order|

### ↔ Flex Wrap

| Class               | Description               |
|---------------------|---------------------------|
| `.flex-wrap`        | Allow wrapping            |
| `.flex-nowrap`      | Disable wrapping          |
| `.flex-wrap-reverse`| Reverse wrap direction    |

### 📦 Justify Content

| Class              | Description                   |
|--------------------|-------------------------------|
| `.justify-start`   | Align items to start (left)   |
| `.justify-center`  | Center items                  |
| `.justify-end`     | Align items to end (right)    |
| `.justify-between` | Equal space between           |
| `.justify-around`  | Equal space around            |
| `.justify-evenly`  | Even spacing between items    |

### 📍 Align Items (Cross-axis)

| Class             | Description               |
|-------------------|---------------------------|
| `.items-start`    | Top-align items           |
| `.items-center`   | Vertically center items   |
| `.items-end`      | Bottom-align items        |
| `.items-baseline` | Align by text baseline    |
| `.items-stretch`  | Stretch to fill container |

### 🧲 Align Content (multi-line)

| Class               | Description                   |
|---------------------|-------------------------------|
| `.content-start`    | Align lines to the top        |
| `.content-center`   | Center lines                  |
| `.content-end`      | Align lines to bottom         |
| `.content-between`  | Space between line groups     |
| `.content-around`   | Space around line groups      |
| `.content-evenly`   | Even spacing in line groups   |

### 🔓 Align Self (per item)

| Class          | Description              |
|----------------|--------------------------|
| `.self-auto`   | Use browser default      |
| `.self-start`  | Align to flex-start      |
| `.self-center` | Align to center          |
| `.self-end`    | Align to flex-end        |
| `.self-stretch`| Stretch to fit           |

# 📐 Layout Utilities

Utility classes for managing layout using Flexbox and CSS Grid.

---

## 🔧 Flexbox Utilities

### Display

| Class         | Description             |
|---------------|-------------------------|
| `.flex`       | `display: flex`         |
| `.inline-flex`| `display: inline-flex`  |

### Flex Direction

| Class               | Description              |
|---------------------|--------------------------|
| `.flex-row`         | `flex-direction: row`    |
| `.flex-col`         | `flex-direction: column` |
| `.flex-row-reverse` | Reversed row direction   |
| `.flex-col-reverse` | Reversed column direction|

### Flex Wrap

| Class               | Description               |
|---------------------|---------------------------|
| `.flex-wrap`        | Wrap items                |
| `.flex-nowrap`      | Prevent wrapping          |
| `.flex-wrap-reverse`| Reverse wrap direction    |

### Justify Content

| Class              | Description               |
|--------------------|---------------------------|
| `.justify-start`   | Align items to start      |
| `.justify-center`  | Center items              |
| `.justify-end`     | Align items to end        |
| `.justify-between` | Space between             |
| `.justify-around`  | Space around              |
| `.justify-evenly`  | Equal spacing             |

### Align Items

| Class             | Description               |
|-------------------|---------------------------|
| `.items-start`    | Align to start (cross-axis) |
| `.items-center`   | Align center               |
| `.items-end`      | Align to end               |
| `.items-baseline` | Align to baseline          |
| `.items-stretch`  | Stretch to fill            |

### Align Content

| Class               | Description               |
|---------------------|---------------------------|
| `.content-start`    | Top-aligned content       |
| `.content-center`   | Centered content          |
| `.content-end`      | Bottom-aligned content    |
| `.content-between`  | Space between lines       |
| `.content-around`   | Space around lines        |
| `.content-evenly`   | Even spacing              |

### Align Self

| Class          | Description           |
|----------------|-----------------------|
| `.self-auto`   | Default alignment     |
| `.self-start`  | Align to start        |
| `.self-center` | Align center          |
| `.self-end`    | Align to end          |
| `.self-stretch`| Stretch to fill       |

---

## 🔲 Grid Utilities

### Display

| Class          | Description           |
|----------------|-----------------------|
| `.grid`        | `display: grid`       |
| `.inline-grid` | `display: inline-grid`|

### Grid Columns

Supports values from `1` to `12`:

```html
.grid-cols-4 → grid-template-columns: repeat(4, minmax(0, 1fr));
```

## 🌫 Shadow Utilities

Apply depth and elevation styles with simple shadow classes.

| Class           | Box Shadow Value                                 |
|------------------|--------------------------------------------------|
| `.shadow-sm`     | `0 1px 2px rgba(0, 0, 0, 0.05)`                  |
| `.shadow`        | `0 1px 3px rgba(0, 0, 0, 0.1)`                   |
| `.shadow-md`     | `0 4px 6px rgba(0, 0, 0, 0.1)`                   |
| `.shadow-lg`     | `0 10px 15px rgba(0, 0, 0, 0.1)`                 |
| `.shadow-xl`     | `0 20px 25px rgba(0, 0, 0, 0.1)`                 |
| `.shadow-2xl`    | `0 25px 50px rgba(0, 0, 0, 0.25)`                |
| `.shadow-inner`  | `inset 0 2px 4px rgba(0, 0, 0, 0.06)`            |
| `.shadow-none`   | `none`                                          |

### 💡 Example

```html
<div class="p-4 shadow-md bg-gray-300 rounded">
  This card has a medium shadow.
</div>
```

## 🧱 Border Utilities

Easily apply consistent borders, styles, and radii.

---

### 📏 Border Widths

| Class        | Value            |
|--------------|------------------|
| `.border`    | `1px`            |
| `.border-0`  | `0`              |
| `.border-2`  | `2px`            |
| `.border-4`  | `4px`            |
| `.border-8`  | `8px`            |

---

### 🔲 Border Sides

| Class        | Description                    |
|--------------|--------------------------------|
| `.border-t`  | `border-top-width: 1px`        |
| `.border-r`  | `border-right-width: 1px`      |
| `.border-b`  | `border-bottom-width: 1px`     |
| `.border-l`  | `border-left-width: 1px`       |
| `.border-x`  | left + right                   |
| `.border-y`  | top + bottom                   |

---

### 🎨 Border Styles

| Class           | Border Style     |
|------------------|------------------|
| `.border-solid`  | `solid`          |
| `.border-dashed` | `dashed`         |
| `.border-dotted` | `dotted`         |
| `.border-double` | `double`         |
| `.border-none`   | `none`           |

---

### 🌐 Border Radius

| Class           | Radius            |
|------------------|------------------|
| `.rounded-sm`    | `0.125rem`        |
| `.rounded`       | `0.25rem`         |
| `.rounded-md`    | `0.375rem`        |
| `.rounded-lg`    | `0.5rem`          |
| `.rounded-xl`    | `0.75rem`         |
| `.rounded-2xl`   | `1rem`            |
| `.rounded-full`  | `9999px`          |

---

### ⬛ Rounded Sides

| Class         | Description                                 |
|---------------|---------------------------------------------|
| `.rounded-t`  | Top-left + top-right border radius          |
| `.rounded-r`  | Top-right + bottom-right border radius      |
| `.rounded-b`  | Bottom-left + bottom-right border radius    |
| `.rounded-l`  | Top-left + bottom-left border radius        |

---

### 💡 Example

```html
<div class="border border-solid border-gray-300 rounded-lg p-4">
  This card has a soft border and rounded corners.
</div>
```


## 📜 License
MIT License © 2025 [Brang Tsawm Aung]

## 🤝 Contributing
Pull requests and issues are welcome! 😊

