# Flow

## 💻 Project
Welcome to **Flow**!

**Flow** is a mobile-responsive Music player app that has many useful features. Users can efficiently upload and edit songs, comment on items, and much more. Data is managed and organised by Firebase, which also provides authentication and data storage.

Please visit (in a new tab): https://flow-dan-chui.vercel.app/

## 🚀 Technologies

- Vue.js
- Vue Router
- Firebase
- Pinia
- PWA
- Tailwind CSS
- Vite
- Testing (Vitest | Cypress)
- Vercel

## 💫 Features

- **Modern Framework**: Utilizing Vue.js and Vue Router to maximise efficiency and reusability.

- **Database**: Data management and storage are delivered by Firebase.

- **Authentication**: Login, editing data and user management requires authentication and authorization. Firebase rule policies controls access.

- **Pinia**: Data-fetching and state management library that simplifies fetching, caching, and updating data.

- **Filtering/Sorting**: Filtering and sorting options via Pinia efficiently navigates through data.

- **PWA**: Progressive Web App (PWA) allows Users to utilize the app both online and offline.

- **UI/UX**: Clean User and mobile-friendly interface stylized by Tailwind CSS.

- **Internationalization**: Vue-i18 assists with translation between the English and Japanese languages.

- **Testing**: Automated testing using Vitest & Cypress helps ensure code quality.

---

## Demo

Please visit (in a new tab): https://flow-dan-chui.vercel.app/

![](/public/assets/img/screenshot1.webp)

![](/public/assets/img/screenshot2.webp)

![](/public/assets/img/screenshot3.webp)

![](/public/assets/img/screenshot4.webp)

![](/public/assets/img/screenshot5.webp)

---

## 🌎 Getting Started

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```

### Run Unit Tests with [Vitest](https://vitest.dev/)

```sh
npm run test:unit
```

### Run End-to-End Tests with [Cypress](https://www.cypress.io/)

```sh
npm run test:e2e:dev
```

This runs the end-to-end tests against the Vite development server.
It is much faster than the production build.

But it's still recommended to test the production build with `test:e2e` before deploying (e.g. in CI environments):

```sh
npm run build
npm run test:e2e
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```
