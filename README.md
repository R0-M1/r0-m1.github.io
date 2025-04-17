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