# Coding Standards

## Naming Conventions

### Components

- Use PascalCase for component names (e.g., `Button`, `ProductCard`).
- Component files are named after the component in PascalCase (e.g., `Button.jsx`).

### Files and Folders

- Component folders: PascalCase (e.g., `Button/`, `ProductCard/`).
- Other folders: camelCase (e.g., `hooks/`, `utils/`, `constants/`).
- Hook files: camelCase prefixed with `use` (e.g., `useCarousel.js`).
- Utility files: camelCase (e.g., `formatters.js`, `validators.js`).
- Constant files: camelCase (e.g., `enums.js`, `routes.js`).

### Variables and Functions

- Use camelCase for variable names, function names, and hook names (e.g., `currentIndex`, `addToCart`, `useCarousel`).

### Constants

- Constant objects: UPPER_CASE (e.g., `ROUTES`, `ORDER_STATUS`).
- Constant keys: ALL_CAPS with underscores (e.g., `HOME`, `PENDING`).

### CSS Classes

- Use kebab-case for CSS class names (e.g., `product-card`, `btn-primary`).

## Formatting Rules

### Indentation

- Use 2 spaces for indentation.

### Code Structure

- Functional components are preferred.
- Use arrow functions for component definitions.
- Destructure props in the function parameters.
- Provide default values for optional props using default parameters.

### Imports

- Import statements at the top of the file.
- Group imports: React imports first, then third-party libraries, then local imports.
- Use relative paths for local imports.

## Component and Folder Structure

### Component Structure

- Each component has its own folder containing the JSX file and CSS file (e.g., `Button/Button.jsx`, `Button/Button.css`).
- Export the component as default.

### Folder Organization

- `components/common/`: Shared, reusable components (e.g., Button, Input).
- `components/features/`: Feature-specific components (e.g., ProductCard).
- `components/layout/`: Layout components (e.g., Header).
- `pages/`: Page-level components for routing.
- `context/`: React context providers.
- `hooks/`: Custom hooks.
- `utils/`: Utility functions.
- `constants/`: Application constants and data.

## State Management Patterns

- Use React Context for global state management (e.g., `AuthContext`, `CartContext`).
- Local state managed with `useState` hook.
- Side effects handled with `useEffect` hook.
- Custom hooks for reusable logic (e.g., `useCarousel`).

## Typing Conventions

- No TypeScript is used; all code is in JavaScript.
- No typing conventions apply.

## CSS Standards and Methodology

- Each component has a dedicated CSS file.
- Use CSS classes for styling, applied via `className` prop.
- Follow a utility-first approach with base classes (e.g., `.btn`) and modifiers (e.g., `.btn-primary`).
- Use CSS custom properties or direct values; no preprocessor like SCSS.

## Testing Conventions

- No testing framework is implemented.
- No testing conventions apply.
