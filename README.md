<div align="center">

  <div>
    <img src="https://img.shields.io/badge/-Next_JS-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=000000" alt="nextdotjs" />
    <img src="https://img.shields.io/badge/-MongoDB-black?style=for-the-badge&logoColor=white&logo=mongodb&color=47A248" alt="mongodb" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
    <img src="https://img.shields.io/badge/-Clerk-black?style=for-the-badge&logoColor=white&logo=clerk&color=6C47FF" alt="clerk" />
    <img src="https://img.shields.io/badge/-Shadcn_UI-black?style=for-the-badge&logoColor=white&logo=shadcnui&color=000000" alt="shadcnui" />
    <img src="https://img.shields.io/badge/-Zod-black?style=for-the-badge&logoColor=white&logo=zod&color=3E67B1" alt="zod" />
    <img src="https://img.shields.io/badge/-Typescript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="typescript" />
  </div>

</div>

- Next.js
- MongoDB
- Shadcn UI
- TailwindCSS
- Clerk
- Webhooks
- Serverless APIs
- React Hook Form
- Zod
- TypeScript

# Project Structure

```
├── app/
│ ├── (auth)/ # Authentication related pages
│ │ ├── onboarding/ # Onboarding page
│ │ ├── page.tsx # Main auth page
│ │ ├── sign-in/[[...sign-in]]/ # Sign-in page
│ │ │ └── page.tsx
│ │ ├── sign-up/[[...sign-up]]/ # Sign-up page
│ │ │ └── page.tsx
│ │ └── layout.tsx # Layout for auth pages
│ └── (root)/ # Root pages
│ ├── api/ # API routes
│ ├── favicon.ico # Favicon
│ ├── globals.css # Global styles
│ ├── components/ # Reusable components
│ │ ├── cards/ # Card components
│ │ ├── forms/ # Form components
│ │ ├── shared/ # Shared components
│ │ └── ui/ # UI components
│ ├── constants/ # Constants
│ ├── lib/ # Utility functions
│ ├── actions/ # Actions
│ ├── models/ # Database models
│ ├── validations/ # Validation logic
│ ├── mongoose.ts # MongoDB connection
│ ├── uploadthing.ts # Uploadthing configuration
│ ├── utils.ts # Utility functions
│ ├── node_modules/ # Node modules
│ └── public/ # Public assets
├── assets/ # Static assets
│ ├── logo.svg # Logo
│ ├── next.svg # Next.js logo
│ └── vercel.svg # Vercel logo
├── .eslintrc.json # ESLint configuration
├── .gitignore # Git ignore file
├── components.json # Components configuration
├── middleware.ts # Middleware
└── next.config.js # Next.js configuration
```
