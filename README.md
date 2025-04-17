# r0-m1.github.io

## Nuxt Project Structure

### 1. **`assets/`**
Contains uncompiled assets like styles, images, and fonts that will be processed during the build.

### 2. **`components/`**
Reusable Vue components (e.g., buttons, cards) used throughout your app.

### 3. **`layouts/`**
Global page structure (e.g., headers, footers). Defines the layout for pages.

### 4. **`pages/`**
Page components. Nuxt automatically creates routes based on `.vue` files here (e.g., `index.vue` = `/`).

### 5. **`public/`**
Static files served directly (e.g., images, PDFs). Accessible at the root of your app.

### 6. **`server/`**
Custom server-side logic, including API routes and server middleware.

### 7. **`static/`**
Another folder for static assets, served without processing (e.g., images).


## Setup

Make sure to install dependencies:

```bash
# npm
npm install

# pnpm
pnpm install

# yarn
yarn install

# bun
bun install
```

## Development Server

Start the development server on `http://localhost:3000`:

```bash
# npm
npm run dev

# pnpm
pnpm dev

# yarn
yarn dev

# bun
bun run dev
```

## Production

Build the application for production:

```bash
# npm
npm run build

# pnpm
pnpm build

# yarn
yarn build

# bun
bun run build
```

Locally preview production build:

```bash
# npm
npm run preview

# pnpm
pnpm preview

# yarn
yarn preview

# bun
bun run preview
```

Check out the [deployment documentation](https://nuxt.com/docs/getting-started/deployment) for more information.
