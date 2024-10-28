# Shorts Generator

An Electron-based desktop application for generating video shorts with custom animations, text, and images.

## Features

- Create shorts-format videos (1080x1920)
- Add and animate text
- Import and transform images
- Timeline-based composition
- Export to MP4

## Installation

```bash
# Clone the repository
git clone https://github.com/Narcis13/YOUR_REPO_NAME.git

# Install dependencies
cd YOUR_REPO_NAME
npm install

# Start the app in development mode
npm run dev

# Build the app for production
npm run build
```

## Development Stack

- Quasar Framework (Vue 3)
- Electron
- TypeScript
- Canvas API
- FFmpeg

## Project Structure

```
├── src/                    # Vue/Quasar source
│   ├── components/         # Reusable components
│   ├── composables/        # Vue composables
│   ├── stores/            # Pinia stores
│   └── pages/             # App pages
├── src-electron/          # Electron-specific code
│   ├── electron-main.ts   # Main process
│   └── electron-preload.ts# Preload scripts
└── package.json
```

## License

MIT

## Author

Narcis13
