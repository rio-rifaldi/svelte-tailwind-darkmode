# Sveltekit + Tailwind CSS + Shadcn svelte Boilerplate with Darkmode

This is a simple boilerplate project for getting started with a web development project using sveltekit and Tailwind CSS, powered by Vite.

## 🎯 Features

- ✅ Vanilla JavaScript: Write modern JavaScript code without any frameworks or libraries.
- ✅ Tailwind CSS: Utilize the power of Tailwind CSS to create highly customizable and responsive UI components.
- ✅ Vite: Enjoy a fast development experience with Vite's blazing-fast build tooling.
- ✅ Darkmode: Darkmode from shadcn svelte

<br><br>

## 🎯 Getting Started

1. Clone the repository:

```sh
git clone https://github.com/jhordyess/svelte-tailwind-darkmode.git
```

2. Navigate to the project folder:

```sh
cd svelte-tailwind-darkmode
```

3. Install dependencies:

```sh
pnpm install
```

4. Start the development server:

```sh
pnpm run dev
```

5. Open your browser and visit [http://localhost:5173](http://localhost:5173) to see your project.

<br><br>

# 📌 Project structure

```md
├── src
│   ├── lib
│   │   ├── components
│   │   │   ├── ui
│   │   │   │   ├── button
│   │   │   │   │   ├── button.svelte
│   │   │   │   │   └── index.ts
│   │   │   │   └── dropdown-menu
│   │   │   │   ├── dropdown-menu-checkbox-item.svelte
│   │   │   │   ├── dropdown-menu-content.svelte
│   │   │   │   ├── dropdown-menu-item.svelte
│   │   │   │   ├── dropdown-menu-label.svelte
│   │   │   │   ├── dropdown-menu-radio-group.svelte
│   │   │   │   ├── dropdown-menu-radio-item.svelte
│   │   │   │   ├── dropdown-menu-separator.svelte
│   │   │   │   ├── dropdown-menu-shortcut.svelte
│   │   │   │   ├── dropdown-menu-sub-content.svelte
│   │   │   │   ├── dropdown-menu-sub-trigger.svelte
│   │   │   │   └── index.ts
│   │   │   └── ThemeToggle.svelte
│   │   ├── index.ts
│   │   └── utils.ts
│   ├── routes
│   │   ├── +layout.svelte
│   │   └── +page.svelte
│   ├── styles
│   │   └── app.css
│   ├── app.d.ts
│   └── app.html
├── static
│   └── favicon-32x32.png
├── README.md
├── components.json
├── eslint.config.js
├── package.json
├── pnpm-lock.yaml
├── postcss.config.js
├── svelte.config.js
├── tailwind.config.ts
├── tsconfig.json
└── vite.config.ts
```

<br><br>

## 🎯 Commands

### Start the development server

```sh
pnpm run dev
```

### Build the project for production

```sh
pnpm run build
```

### Preview the project before production

```sh
pnpm run preview
```

## 🎯 Contributing

Contributions are welcome! If you find any issues or want to enhance the project, feel free to submit a pull request.

---

Happy coding!
