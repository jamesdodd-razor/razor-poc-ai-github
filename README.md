# razor-poc-ai-github

A simple Hello World project built with Nuxt 3 and Tailwind CSS.

## Features

- Clean, modern design using Tailwind CSS
- Responsive layout
- Component-based architecture with reusable Vue components
- Powered by Nuxt 3 framework for server-side rendering, file-based routing, and enhanced development experience
- Hot module replacement (HMR) for instant feedback during development
- Built-in support for composables and Vue 3 Composition API

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

- **Pages:** Add new pages by creating `.vue` files in the `pages/` directory. Nuxt 3 automatically generates routes based on file structure.
- **Components:** Reusable components should be placed in the `components/` directory. They can be used anywhere in your pages or layouts.
- **Composables:** For reusable logic, add composable functions to the `composables/` directory.
- **Layouts:** To customize the page layout, edit or add layouts in the `layouts/` directory and specify them in your page components.
- **Configuration:** Update `nuxt.config.ts` to manage Nuxt modules, plugins, and runtime configuration.
- **Build for Production:** To generate a production build, run:

  ```bash
  npm run build
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
└── pages
    └── index.vue
```

- `components/`: Reusable Vue components
- `composables/`: Utility functions and composables for Vue 3 Composition API
- `layouts/`: Layout components for page structure
- `pages/`: Page components mapped to routes
- `nuxt.config.ts`: Nuxt 3 configuration file

## Contributing

Contributions are welcome! Please open issues or pull requests for improvements and bug fixes.

## License

[MIT](LICENSE)
