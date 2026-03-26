# Cyan for Fluxer

Powerful UX, stunning visuals, like never before.

A modern theme for Fluxer built with Tailwind CSS and Sass, using the Cyan Design.

## Requirements

- [Node.js](https://nodejs.org/) (v18 or higher)
- [pnpm](https://pnpm.io/) (v10.32.1 or higher)

## Installation

1. Clone the repository
2. Install dependencies:

```bash
pnpm install
```

## Building

### Build Once

To build the theme once:

```bash
pnpm run build
```

This compiles `src/index.css` using PostCSS and outputs the result to `import.css`.

### Watch Mode

To build the theme and watch for changes during development:

```bash
pnpm run build:watch
```

This will continuously rebuild the theme whenever you make changes to the source files, with verbose logging enabled.

## Project Structure

- `src/index.css` - Main theme entry point
- `import.css` - Generated output (created after building)
- `postcss.config.js` - PostCSS configuration

## Dependencies

- **Tailwind CSS** - Utility-first CSS framework
- **PostCSS** - CSS transformation tool
- **Sass** - CSS preprocessor
- **@cyandesign/core** - Basic stylesheets and utility classes for the Cyan Design Language

## License

MIT
