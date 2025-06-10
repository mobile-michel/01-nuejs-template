# NueJS Site

A minimal website built with [NueJS](https://nuejs.org), a modern static site generator.

## Features

- Simple and intuitive
- Markdown support
- YAML configuration
- Fast build times
- Clean output

## Local Development

This project uses [Bun](https://bun.sh) as the package manager and runtime.

```bash
# Start development server
nue

# Build for production
nue build -p
```

## Deployment

This site is deployed on [Netlify](https://netlify.com). The build process is configured in `netlify.toml`.

## Project Structure

```
.
├── index.md          # Main content
├── site.yaml         # Site configuration
├── styles.css        # Global styles
├── package.json      # Project dependencies
└── netlify.toml      # Netlify configuration
```

## License

MIT 