# Ron Gustafsson – Portfolio

Personal software developer portfolio built with Next.js, React, TypeScript, and Tailwind CSS.

The portfolio is designed to present my technical skills, projects, experience, education, and development direction toward full-stack and AI-focused software development.

The portfolio itself also serves as a practical software development project and technical demonstration.

## Tech Stack

- **Next.js 16** – application framework and static site generation
- **React 19** – component-based user interface
- **TypeScript** – static typing
- **Tailwind CSS 4** – styling and responsive design
- **ESLint** – code quality and static analysis
- **Prettier** – consistent code formatting
- **pnpm** – package management

Additional UI libraries and tools will be added only when needed during development.

## Development

### Requirements

- Node.js 24 or compatible version
- pnpm 12

### Install dependencies

```bash
pnpm install
```

### Start the development server

```bash
pnpm dev
```

Open:

```text
http://localhost:3000
```

The application automatically reloads when source files are changed.

## Available Commands

```bash
pnpm dev
```

Starts the Next.js development server.

```bash
pnpm build
```

Creates the production build and static export.

```bash
pnpm lint
```

Checks the source code with ESLint.

```bash
pnpm lint:fix
```

Automatically fixes ESLint issues when possible.

```bash
pnpm format
```

Formats supported project files with Prettier.

```bash
pnpm format:check
```

Checks that project files follow the configured Prettier formatting rules without modifying them.

## Project Structure

```text
portfolio/
├── .vscode/          # Project-specific VS Code settings and extension recommendations
├── app/              # Next.js App Router pages, layouts and global styles
├── docs/             # Portfolio design and technical planning documentation
├── public/           # Static assets
├── eslint.config.mjs # ESLint configuration
├── next.config.ts    # Next.js configuration and static export settings
├── prettier.config.mjs
├── package.json
└── tsconfig.json
```

The structure will expand as reusable UI components and portfolio sections are implemented.

## Code Quality

The development environment is configured with:

- ESLint for code quality checks
- Prettier for automatic formatting
- Tailwind CSS IntelliSense for Tailwind development
- project-specific VS Code settings
- automatic formatting and ESLint fixes when files are saved

Before committing significant changes, the project can be verified with:

```bash
pnpm lint
pnpm format:check
pnpm build
```

## Static Export

The portfolio is configured as a static Next.js site:

```ts
output: "export";
```

Running:

```bash
pnpm build
```

generates the deployable static site in:

```text
out/
```

The production site therefore does not require a Node.js server or Next.js server-side runtime.

## Deployment

The planned production hosting platform is **StaticHost.eu**.

The custom domain will be connected after the portfolio reaches a publishable version.

## Project Status

**In development**

Current focus:

- development environment and project foundation
- design system and global styles
- page structure
- responsive UI implementation
- portfolio content and project case studies

Planned main sections include:

- Hero
- About
- Thinking and working approach
- Technical skills
- Experience and education
- Projects
- Current development focus
- Contact

## Author

**Ron Gustafsson**  
Software Developer

- GitHub: https://github.com/Ron-Gustafsson
- LinkedIn: https://www.linkedin.com/in/ron-gustafsson/