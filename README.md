# razor-poc-ai-github

A modern Hello World project built with Nuxt 3 and Tailwind CSS.

## Features

- **Powered by [Nuxt 3](https://nuxt.com/):** Enjoy server-side rendering, file-based routing, and a streamlined developer experience.
- **Tailwind CSS Integration:** Effortless styling with [Tailwind CSS](https://tailwindcss.com/) via Nuxt module.
- **Responsive Design:** Mobile-friendly layouts out of the box.
- **Component-Based Architecture:** Leverage reusable Vue 3 components.
- **Hot Module Replacement (HMR):** Instant feedback during development.
- **Automatic Routing & Layouts:** Nuxt 3 conventions for pages and layouts.
- **Vue 3 Composition API:** Use composables for reusable logic—auto-imported by Nuxt 3.
- **Efficient Workflows:** Optimized build, development, and deployment processes tailored for Nuxt 3.

## Setup

1. **Clone this repository**

   ```bash
   git clone https://github.com/your-username/razor-poc-ai-github.git
   cd razor-poc-ai-github
   ```

2. **Install dependencies**

   ```bash
   npm install
   # or
   yarn install
   ```

3. **Run the development server**

   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. **Open your browser** and navigate to [http://localhost:3000](http://localhost:3000)

## Usage Guidelines

- **Pages:** Create new pages by adding `.vue` files in the `pages/` directory. Nuxt 3 automatically generates routes based on file structure.
- **Components:** Place reusable Vue components in the `components/` directory. Nuxt 3 auto-imports these across your project.
- **Composables:** For reusable logic, add functions to the `composables/` directory (auto-imported, leveraging the Vue 3 Composition API).
- **Layouts:** Customize app structure by modifying or adding layouts in the `layouts/` directory. Assign a layout in a page component using the `definePageMeta` function.
- **Configuration:** Manage Nuxt modules, plugins, and runtime settings in `nuxt.config.ts`. Tailwind CSS is integrated as a Nuxt module; customize via `tailwind.config.js` if needed.
- **Environment Variables:** Add environment variables in a `.env` file. Nuxt 3 reads these automatically and exposes them via `useRuntimeConfig()`.
- **Production Build:** Generate and preview a production build with:

  ```bash
  npm run build
  npm run preview
  # Or for Node hosting:
  npm run start
  ```

## Technologies Used

- [Nuxt 3](https://nuxt.com/) — Vue 3 framework with server-side rendering and file-based routing
- [Vue 3](https://vuejs.org/)
- [Tailwind CSS](https://tailwindcss.com/) — integrated via Nuxt module
- [Node.js](https://nodejs.org/)

## Project Structure

```
.
├── .gitignore
├── README.md
├── components
│   └── HelloCard.vue
├── composables
│   └── (your composables here)
├── layouts
│   └── default.vue
├── nuxt.config.ts
├── package.json
├── pages
│   └── index.vue
├── app.vue
├── tailwind.config.js
└── tsconfig.json
```

- `components/`: Reusable Vue 3 components (auto-imported)
- `composables/`: Reusable logic and Vue 3 Composition API functions (auto-imported)
- `layouts/`: Layout components for consistent page structure
- `pages/`: Route-mapped page components
- `nuxt.config.ts`: Nuxt 3 configuration file
- `app.vue`: Root Vue component for global structure
- `tailwind.config.js`: Tailwind CSS configuration (customize if needed)
- `tsconfig.json`: TypeScript configuration (Nuxt 3 supports TypeScript by default)

## Configuration

- **Nuxt 3 Config:** All Nuxt modules, plugins, and runtime configuration are managed in `nuxt.config.ts`. Tailwind CSS is included as a Nuxt module. For further Tailwind customization, use `tailwind.config.js`.
- **Environment Variables:** Use a `.env` file to manage sensitive or environment-specific variables. Access them in code via Nuxt's `useRuntimeConfig()` composable or `runtimeConfig` in `nuxt.config.ts`.

## Contributing

Contributions are welcome! Please open issues or pull requests for improvements and bug fixes.

## License

[MIT](LICENSE)
