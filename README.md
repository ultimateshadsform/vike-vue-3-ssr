# Vike Vue 3 SSR App

This is a Vue 3 SSR (Server-Side Rendering) app built with Vike, Hono, and deployed to production.

## Development

To start the development server, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/ultimateshadsform/vike-vue-3-ssr-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd vike-vue-3-ssr-app
   ```
3. Install dependencies:
   ```bash
   bun install
   ```
4. Start the development server:
   ```bash
   bun dev
   ```
5. Open your browser and visit `http://localhost:3000` to see the app in action.

## Building for Production

To build the app for production, run the following command:

```bash
bun prod
```

This will generate a `dist` directory containing the production-ready files.

As you can see in the devtools you can see it is using Hono with the `Server` http header.
