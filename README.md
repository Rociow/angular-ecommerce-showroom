# Venecia Showroom - E-Commerce Angular

A web-based e-commerce application built with Angular 20, designed to browse clothing items, filter products, and manage a shopping cart. The project follows a modular structure using reusable components, HTTP services, and dynamic routing.

## Descripción

Venecia Showroom is an interactive online shop created as a learning project.
The application fetches product data from an external API (MockAPI) and provides a complete shopping experience with navigation, item visualization, and cart management.

## Key features:
- 📱 Modern and responsive UI
- 🛒 Fully functional shopping cart
- 📦 Dynamic product listing sourced from an API
- 🔀 Routing between multiple views
- 📝 Modular and reusable components

## Project Structure:

```
src/app/
├── app.ts                 # Root component
├── app-module.ts          # Main module
├── app-routing-module.ts  # App routing configuration
├── cart.ts                # Cart logic
├── products-data.ts       # Products service (API interaction)
├── input-integer/         # Numeric input component
├── product-about/         # Product details component
├── product-cart/          # Cart component
├── product-list/          # Product listing component
└── product-products/      # Products component
```

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

