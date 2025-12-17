# Build, Test, and Lint Commands

## npm/yarn Scripts

The project uses npm for package management. The following scripts are defined in `package.json`:

### Development Server

- Command: `npm run dev` or `yarn dev`
- Description: Starts the Vite development server.
- Expected Outcome: Launches a local development server (typically at `http://localhost:5173`).
- Common Flags: None commonly used.
- Troubleshooting: If the port is in use, Vite will prompt to use a different port or kill the process.

### Build

- Command: `npm run build` or `yarn build`
- Description: Builds the application for production using Vite.
- Expected Outcome: Creates a `dist/` directory with optimized, bundled files.
- Common Flags: None commonly used.
- Troubleshooting: Ensure all dependencies are installed. If build fails due to missing assets, check file paths.

### Lint

- Command: `npm run lint` or `yarn lint`
- Description: Runs ESLint on the entire codebase.
- Expected Outcome: Reports any linting errors or warnings in the console.
- Common Flags: None commonly used.
- Troubleshooting: Fix reported errors by adhering to the coding standards. Use `--fix` flag if ESLint supports auto-fixing for some rules.

### Preview

- Command: `npm run preview` or `yarn preview`
- Description: Previews the built application locally.
- Expected Outcome: Serves the `dist/` directory on a local server.
- Common Flags: None commonly used.
- Troubleshooting: Run `npm run build` first if the `dist/` directory is missing.

## Testing Tools

- No testing tools or scripts are configured in the repository.
- No test commands are available.

## CI/CD Configuration

- No CI/CD configuration files are present in the repository.
