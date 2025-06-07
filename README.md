# razor-poc-ai-github

A modern Hello World project now powered by Nuxt 3 and Tailwind CSS.

## Features

- **Built with [Nuxt 3](https://nuxt.com/):** Server-side rendering, file-based routing, and a modern developer experience.
- **Tailwind CSS Integration:** Effortless utility-first styling via the official Nuxt module.
- **Responsive Design:** Mobile-first layouts out of the box.
- **Component-Based Architecture:** Reusable Vue 3 components for maintainability.
- **Hot Module Replacement (HMR):** Rapid development with instant feedback.
- **Automatic Routing & Layouts:** Pages and layouts managed by Nuxt conventions for streamlined navigation.
- **Vue 3 Composition API:** Use auto-imported composables for reusable logic.
- **Optimized Workflows:** Fast builds, development, and deployment tailored for Nuxt 3.
- **Environment Variable Support:** Secure, flexible configuration using `.env` files and Nuxt runtime config.

## Setup

1. **Clone the repository**

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

- **Pages:** Create new routes by adding `.vue` files to the `pages/` directory. Nuxt 3 auto-generates routes based on the file structure.
- **Components:** Place reusable Vue components in the `components/` directory. Nuxt 3 auto-imports these globally.
- **Composables:** Add reusable logic/functions in the `composables/` directory. These are auto-imported via the Vue 3 Composition API.
- **Layouts:** Modify or add layouts in the `layouts/` directory for consistent page structures. Assign a layout using the `definePageMeta` function in each page.
- **Configuration:** Manage Nuxt modules, plugins, and runtime settings in `nuxt.config.ts`. Tailwind CSS is installed as a Nuxt module; further customize via `tailwind.config.js`.
- **Environment Variables:** Store sensitive or environment-specific variables in a `.env` file. Access them via Nuxt's `useRuntimeConfig()` composable.
- **Production Build:** Build and preview a production-ready application with:

  ```bash
  npm run build
  npm run preview
  # Or for Node hosting:
  npm run start
  ```

## Technologies Used

- [Nuxt 3](https://nuxt.com/) — Vue 3 framework with SSR and file-based routing
- [Vue 3](https://vuejs.org/)
- [Tailwind CSS](https://tailwindcss.com/) — via Nuxt module
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
- `nuxt.config.ts`: Nuxt 3 project configuration
- `app.vue`: Root Vue component for customizing global structure
- `tailwind.config.js`: Tailwind CSS configuration (customize if needed)
- `tsconfig.json`: TypeScript configuration (Nuxt 3 supports TypeScript out of the box)

## Configuration

- **Nuxt 3 Config:** All Nuxt modules, plugins, and runtime configuration are managed in `nuxt.config.ts`. Tailwind CSS is configured as a Nuxt module. For additional Tailwind customization, edit `tailwind.config.js`.
- **Environment Variables:** Use a `.env` file to manage sensitive or environment-specific variables. Access them in code using Nuxt's `useRuntimeConfig()` composable or through `runtimeConfig` in `nuxt.config.ts`.

## Migration Notes

This project was migrated from a static HTML/CSS setup to a Nuxt 3 application. Legacy static files have been removed or refactored into Vue single-file components. Please refer to the new structure and usage guidelines above for working with the Nuxt ecosystem.

## Contributing

Contributions are welcome! Please open issues or pull requests for improvements and bug fixes.

## License

[MIT](LICENSE)
