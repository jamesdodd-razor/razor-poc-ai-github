# razor-poc-ai-github

A simple Hello World project built with Nuxt 3 and Tailwind CSS.

## Features

- Built on [Nuxt 3](https://nuxt.com/) for server-side rendering, file-based routing, and enhanced developer experience
- Clean, modern design using [Tailwind CSS](https://tailwindcss.com/) via Nuxt module integration
- Responsive layout out of the box
- Component-based architecture with reusable Vue 3 components
- Hot module replacement (HMR) for instant feedback during development
- Built-in support for composables and the Vue 3 Composition API
- Easy route generation and layouts with Nuxt 3 conventions
- Efficient development workflows tailored for Nuxt 3

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

- **Pages:** Add new pages by creating `.vue` files in the `pages/` directory. Nuxt 3 automatically generates routes based on the file structure.
- **Components:** Place reusable Vue components in the `components/` directory. These can be used anywhere in your pages or layouts, leveraging Nuxt 3's auto-import feature.
- **Composables:** For reusable logic, add composable functions to the `composables/` directory. These utilize the Vue 3 Composition API and are auto-imported by Nuxt 3.
- **Layouts:** Customize your app's structure by editing or adding layouts in the `layouts/` directory. Specify layouts in your page components with the `definePageMeta` function.
- **Configuration:** Manage Nuxt modules, plugins, and runtime settings in `nuxt.config.ts`. Tailwind CSS is integrated as a Nuxt module, so additional Tailwind configuration can be handled here or in a separate `tailwind.config.js` file.
- **Build for Production:** Generate and preview a production build with:

  ```bash
  npm run build
  npm run preview
  # Or for Node hosting:
  npm run start
  ```

## Technologies Used

- [Nuxt 3](https://nuxt.com/) (Vue 3 framework with server-side rendering and file-based routing)
- [Vue 3](https://vuejs.org/)
- [Tailwind CSS](https://tailwindcss.com/) (integrated via Nuxt module)
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

- `components/`: Reusable Vue components (auto-imported)
- `composables/`: Utility functions and composables for Vue 3 Composition API (auto-imported)
- `layouts/`: Layout components for page structure
- `pages/`: Page components mapped to routes
- `nuxt.config.ts`: Nuxt 3 configuration file
- `app.vue`: Root Vue component for global app structure
- `tailwind.config.js`: Tailwind CSS configuration (if custom config is needed)
- `tsconfig.json`: TypeScript configuration (Nuxt 3 supports TypeScript out of the box)

## Configuration

- **Nuxt 3 Configuration:** All Nuxt modules, plugins, and runtime configuration should be managed in `nuxt.config.ts`. Tailwind CSS is added via the Nuxt module. If you need to customize Tailwind, use `tailwind.config.js`.
- **Environment Variables:** Place environment variables in a `.env` file or configure them in `nuxt.config.ts` under `runtimeConfig`.

## Contributing

Contributions are welcome! Please open issues or pull requests for improvements and bug fixes.

## License

[MIT](LICENSE)
