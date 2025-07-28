# 🧱 nextjs-template

A modern and minimal **Next.js 15** starter template featuring **React 18**, **Tailwind CSS**, **TypeScript**, and **Turbopack**. Ideal for building fast, scalable, and maintainable web applications.

---

## 🚀 Features

- ⚡️ **Next.js 15.4.4** with [Turbopack](https://turbo.build/pack) for blazing-fast dev performance
- 💨 **Tailwind CSS 3.4** – utility-first CSS framework
- 🔒 **TypeScript** for static typing
- ✅ **ESLint** with Next.js config
- 🧪 Ready-to-go development, linting, and production setup

---

## 📦 Tech Stack

| Tool            | Version    |
|-----------------|------------|
| Next.js         | 15.4.4     |
| React           | 18.3.1     |
| TypeScript      | ^5         |
| Tailwind CSS    | 3.4.17     |
| ESLint          | ^9         |
| PostCSS         | ^8.5.6     |
| Turbopack       | Enabled via `next dev --turbopack` |

---

## 📂 Project Structure

```

.
├── public/             # Static files
├── src/                # App source code (if using `src` dir structure)
│   ├── pages/          # Next.js pages
│   ├── styles/         # Tailwind & global styles
│   └── components/     # React components (optional)
├── tailwind.config.js  # Tailwind CSS config
├── postcss.config.js   # PostCSS config
├── tsconfig.json       # TypeScript config
├── next.config.js      # Next.js config
└── package.json

````

---

## 🛠️ Scripts

```bash
# Start development server with Turbopack
npm run dev

# Create optimized production build
npm run build

# Start production server
npm run start

# Run ESLint checks
npm run lint
````

---

## 🧰 Getting Started

1. **Clone the repository:**

```bash
git clone https://github.com/itsbhm/nextjs-template.git
cd nextjs-template
```

2. **Install dependencies:**

```bash
npm install
# or
yarn install
```

3. **Start the dev server:**

```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) to see your app.

---

## 🧪 Linting

This template comes with ESLint configured using the official Next.js plugin:

```bash
npm run lint
```

You can customize ESLint rules in `.eslintrc`.

---

## 🌐 Deployment

This template can be deployed to any platform that supports Node.js. Popular choices:

* [Vercel](https://vercel.com) (official Next.js hosting)
* [Netlify](https://netlify.com)
* [Render](https://render.com)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 💡 Customization Tips

* Use the `src/` directory pattern for better separation (optional)
* Add `@/` aliasing in `tsconfig.json` and `next.config.js` for cleaner imports
* Integrate testing tools like Jest or Playwright as needed

---

🧑‍💻 **Author**: [@itsbhm](https://github.com/itsbhm)
