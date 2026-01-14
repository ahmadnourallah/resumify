# Resumify

An advanced, responsive CV builder powered by React and React PDF.

## Demo

<div align="center">
    <img src="https://github.com/ahmadnourallah/portfolio/blob/main/src/assets/resumify.webp?raw=true" height="800">
</div>

Check out the live version deployed on GitHub Pages
[here](https://ahmadnourallah.github.io/resumify).

## Description

Resumify strives to offer an efficient and viable product in the field of CV creation, but without being too consuming for the product operators. It does so by offering all the capabilities that CV builders usually present to their users; however, it delegates the process of PDF creation itself to the client using React PDF.

This way, the user has all they need to create a professional resume, and the product operator can deploy the service with low to zero costs as they do not need to allocate computational power to the process of PDF creation (i.e., they can use static hosting). Moreover, it ensures that PDF creation on the client is non-blocking by utilizing the Web Workers API.

Resumify features an intuitive GUI that makes CV creation accessible to everyone. It provides users with instant preview. The preview system is built with native HTML to ensure instant synchronization.

## Features

-   :white_check_mark: In-client, non-blocking PDF generation on the fly using React PDF and the Web Workers API.
-   :white_check_mark: Instant preview in the browser with native HTML elements.
-   :white_check_mark: Intuitive, easy-to-use GUI that makes CV creation accessible to everyone.
-   :white_check_mark: Utilizes Immer for safe state mutation.
-   :white_check_mark: Instant file saving on demand.

## Getting Started

### Installation

1. Clone the repository:

```bash
git clone https://github.com/ahmadnourallah/resumify
```

2. Install dependencies:

```bash
npm install
```

### Deployment

You can fire up the development server using:

```bash
npm run dev
```

Building the application can be done by running:

```bash
npm run build
```

You can preview the production build through:

```bash
npm run preview
```

Since it works on the client entirely, you can host Resumify using a static
hosting service, such as GitHub Pages or Vercel. Check out
[this workflow](https://github.com/ahmadnourallah/resumify/blob/main/.github/workflows/deploy.yml)
to get an idea about how to deploy the project to GitHub Pages through Actions.

## Technologies

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=js,react,vite" />
  </a>
</p>

The system is built with the latest technologies:

-   JavaScript
-   React
-   Vite
-   React PDF
-   Immer

## License

This project is licensed under the GNU GPLv3 License - see the LICENSE.md file
for details.
