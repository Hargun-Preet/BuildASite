# BuildASite
BuildASite is a powerful, user-friendly web application that allows developers to quickly create React-based applications by giving simple prompts. Whether you're building a prototype or starting a new project, this tool simplifies the process by generating fully functional React apps with just a few clicks.
This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Live Link
Check out my project: [Build A Site](https://build-a-site.netlify.app/)

## Getting Started
## Setup .env.local File
To get started with the app, you'll need to create a .env.local file in the root of your project. This file contains sensitive keys and configuration values for your app.

Steps to Create .env.local:
1. Create a .env.local file in the root directory of your project.
2. Add the following environment variables to the .env.local file:
```bash
  NEXT_PUBLIC_GOOGLE_AUTH_CLIENT_ID=your-google-auth-client-id  
  CONVEX_DEPLOYMENT=your-convex-deployment-id  
  NEXT_PUBLIC_CONVEX_URL=your-convex-url  
  NEXT_PUBLIC_PAYPAL_CLIENT_ID=your-paypal-client-id  
  GEMINI_API_KEY=your-gemini-api-key  
  ```
Replace the placeholder values (your-google-auth-client-id, your-convex-deployment-id, etc.) with your actual keys.

## Notes:
```bash
  NEXT_PUBLIC_GOOGLE_AUTH_CLIENT_ID: Your Google OAuth client ID for authentication.
  CONVEX_DEPLOYMENT: Your Convex deployment ID.
  NEXT_PUBLIC_CONVEX_URL: URL for connecting to Convex services.
  NEXT_PUBLIC_PAYPAL_CLIENT_ID: Your PayPal client ID for payment integrations.
  GEMINI_API_KEY: Your Gemini API key for accessing crypto data.
 ```
Once you've set up the .env.local file, restart the app to apply the changes.

## Running the App

1. First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```
2. In another terminal run:
```bash
npm convex dev
```
Configure a new or existing project and complete the prompts.

3. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!


Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
