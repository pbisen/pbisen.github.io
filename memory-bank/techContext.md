# Technical Context

## Core Technologies
- **Framework**: Quartz v4
- **Language**: TypeScript
- **UI Library**: React
- **Styling**: SCSS
- **Build Tools**: Node.js
- **Version Control**: Git
- **Hosting**: GitHub Pages

## Development Setup
- Node.js environment required
- Package management via npm
- Local development server support
- Docker container available for consistent environments

## Dependencies
Key dependencies identified from package.json:
- TypeScript for type-safe development
- React for component-based UI
- SCSS for styling
- Various Quartz-specific plugins and components

## Project Structure
```
.
├── content/            # Main content directory
├── docs/              # Documentation
├── quartz/            # Core Quartz framework files
│   ├── components/    # React components
│   ├── plugins/       # Quartz plugins
│   ├── styles/        # SCSS styling
│   └── util/          # Utility functions
└── templates/         # Content templates
```

## Build Process
- TypeScript compilation
- Static site generation
- Asset processing
- Plugin transformations

## Technical Constraints
1. Must maintain compatibility with Quartz's plugin system
2. Should follow TypeScript best practices
3. Must be deployable to GitHub Pages
4. Should maintain responsive design principles
5. Must support various Markdown flavors (Obsidian, GitHub, etc.)

## Tool Usage Patterns
1. Development Commands:
   - `npm install` for dependency installation
   - `npm run dev` for local development
   - `npm run build` for production builds
   
2. Content Management:
   - Markdown files in content/ directory
   - Asset management through static/ directory
   - Configuration through quartz.config.ts and quartz.layout.ts

3. Component Development:
   - TypeScript/React components in quartz/components/
   - SCSS styling in quartz/styles/
   - Plugin development in quartz/plugins/

4. Version Control:
   - Git-based workflow
   - GitHub repository hosting
   - GitHub Pages deployment

## Configuration Files
- quartz.config.ts: Main configuration
- quartz.layout.ts: Layout configuration
- tsconfig.json: TypeScript configuration
- package.json: Project dependencies and scripts
