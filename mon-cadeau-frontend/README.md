# Mon Cadeau (front-end)
This is a MVP for a gift organizer mobile and web app

## 🌟 Features

* User authentication (login, logout)
* Dashboard showing profile, groups and wishlist
* Create, view, edit, delete users, groups and wishlists
* Responsive UI for desktop and mobile
* API integration using REST

## 🧱 Tech Stack

* **Framework / Library**: NextJS
* **Styling**: Tailwind CSS
* **HTTP Client**: Axios
* **State Management**: Context API
* **Form Handling**: Reactive Forms
* **Routing**: Next Router
* **Linting / Formatting**: ESLint, Prettier

## 🔧 Getting Started

First, run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

### Prerequisites

* Node.js v20+
* npm

### Setup

1. **Clone the repo**

   ```bash
   git clone https://github.com/rafonha/mon-cadeau
   cd mon-cadeau-frontend
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Run the development server**

   ```bash
   npm start
   # or
   yarn dev
   ```

   The app should be available at `http://localhost:3000` (or the configured port).

## 📱 Application Overview

### Core Pages / Components

* **Login / Authentication**: Secure access with form validation
* **Dashboard**: Summary of profile, groups, wishlists
* **Group List**: View all groups, search, select
* **Group Detail**: View/edit individual group info and wishlist
* **Wishlist**: Create and manage wishlist

### API Integration

Example of API usage in React (adjust for your stack):

```js
// Example with Axios
axios.get(`${process.env.REACT_APP_API_URL}/groups`, {
  headers: { Authorization: `Bearer ${token}` }
});
```

## 🎨 Styling & Assets

* Uses **Tailwind CSS** for utility-first styling
* Custom components for forms, modals, navigation, and cards
* Responsive design via CSS grid/flexbox

## 🛡️ Testing & Quality

* **Linting** with ESLint:

  ```bash
  npm run lint
  ```
* **Formatting** with Prettier:

  ```bash
  npm run format
  ```
* **UI / Integration Tests** using Jest + React Testing Library (adjust as needed):

  ```bash
  npm test
  ```

## 🚀 Deployment

Example using **Netlify / Vercel / GitHub Pages**:

```bash
npm run build
# deploy the build folder to your preferred host
```

Set environment variables (like `REACT_APP_API_URL`) on your host for correct API integration.

## 📝 License

Distributed under \MIT License. See `LICENSE` for details.

