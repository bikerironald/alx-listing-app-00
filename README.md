# ALX Listing App 

Creating an Airbnb clone listing page.


Here's a brief explanation of the project structure, I've set it up with custom folders like `components/`, `interfaces/`, `constants/`, and `public/assets/`:


### 🗂️ **Project Structure Overview**

```
my-next-app/
├── components/
├── interfaces/
├── constants/
├── public/
│   └── assets/
├── pages/
├── styles/
├── utils/
├── app/ or pages/ (depending on the routing setup)
├── next.config.js
├── tsconfig.json (if using TypeScript)
└── package.json
```

---

### 📁 `components/`

**Purpose:**
Holds reusable React components that make up the UI of your application.

**Examples:**

* `Button.tsx` – A styled button used across the site.
* `Card.tsx` – A UI card component for displaying content blocks.

**Benefit:**
Encourages modularity and reusability across pages.

---

### 📁 `interfaces/` (or sometimes `types/`)

**Purpose:**
Stores TypeScript interfaces and types used throughout the app.

**Examples:**

* `User.ts` – Defines the shape of a User object.
* `Post.ts` – Describes a blog post or article.

**Benefit:**
Centralizes type definitions for consistency and type safety.

---

### 📁 `constants/`

**Purpose:**
Contains fixed values used in multiple parts of the app.

**Examples:**

* `routes.ts` – Defines route paths as constants.
* `config.ts` – App-wide config like API base URLs.
* `messages.ts` – Static text like error or success messages.

**Benefit:**
Prevents hardcoding values and improves maintainability.

---

### 📁 `public/assets/`

**Purpose:**
Stores static files (like images, icons, and fonts) that can be publicly accessed.

**Examples:**

* `logo.png` – Used in the site's header or metadata.
* `background.jpg` – Used as a hero background image.
* `icons/` – Custom icons in SVG or PNG format.

**How it's accessed in the app:**

```jsx
<img src="/assets/logo.png" alt="Logo" />
```

**Benefit:**
Publicly accessible and doesn't require import statements.



## How to run project

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
