# Mathlet

Mathlet is a project by Christian and Philip. This project is built using Astro.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have installed [Node.js](https://nodejs.org/) (version 18 or higher).
- You have installed [pnpm](https://pnpm.io/) (version 7.1.0 or higher).

## Setup

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/mathlet.git
    cd mathlet
    ```

2. Install dependencies:
    ```sh
    pnpm install
    ```

## Usage

### Development

To start the development server, run:
    ```sh
    pnpm run dev
    ```

### Build

To build the project, run:
    ```sh
    pnpm run build
    ```

### Preview

To preview the build, run:
    ```sh
    pnpm run preview
    ```

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
├── src/
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.
