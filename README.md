# Exam Material Archive

![Website Screenshot](/public/screenshot.PNG)

This project provides an improved interface for accessing and searching the **State Examinations Commission's Exam Material Archive**. It is built using [Astro](https://astro.build).

## 🌟 Features

- **Responsive Design**: Optimized for both desktop and mobile devices.
- **Dynamic Dropdowns**: Select examination types, subjects, and years with interactive dropdowns that don't change when changing the subject.
- **Deferred Year Support**: Handles deferred examination papers dynamically.

## 🚀 Project Structure

The project is organized as follows:

```text
/
├── public/                     # Static assets
│   ├── favicon.ico             # Favicon for the site
│   ├── logo.jpg                # Logo used in meta tags
│   └── background.svg          # Background image
├── src/
│   ├── components/             # Reusable components
│   │   ├── mainContainer.astro # Main page container
│   │   ├── paperContainer.astro # Papers page container
│   │   └── subcomponents/      # Smaller reusable components
│   ├── layouts/                # Layout components
│   │   ├── Layout.astro        # Main layout
│   │   └── paperButtonLayout.astro # Layout for grouped buttons
│   └── pages/                  # Pages of the site
│       ├── index.astro         # Homepage
│       └── papers.astro        # Papers page
├── .astro/                     # Astro-generated types and configs
├── .github/workflows/          # GitHub Actions for deployment
├── .vscode/                    # VS Code workspace settings
├── package.json                # Project dependencies and scripts
├── astro.config.mjs            # Astro configuration
├── tsconfig.json               # TypeScript configuration
└── .prettierrc                 # Prettier configuration
```

## 🧞 Commands

Run the following commands from the root of the project:

| Command           | Action                                            |
| :---------------- | :------------------------------------------------ |
| `npm install`     | Installs dependencies                             |
| `npm run dev`     | Starts the development server at `localhost:4321` |
| `npm run build`   | Builds the project for production                 |
| `npm run preview` | Previews the production build locally             |
| `npm run format`  | Formats the codebase using Prettier               |

## 🌐 Deployment

This project is deployed using **GitHub Pages**. The deployment workflow is defined in [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml).

## 📜 License and Disclaimer

All examination materials are the copyright of the **State Examinations Commission (SEC)**. This project does not claim ownership of the materials and complies with the SEC's terms of use. For more details, see the [LICENSE.md](LICENSE.md) file.

## 🎯 TODO

- Add a search bar to the subjects dropdown for easier navigation.

## Code and bug reporting

You can open an issue at https://github.com/Arisamiga/Examinations
