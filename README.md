# VerifEye
A verifiability tool for social media platforms that serves short-form video content.

## Prerequisites
The following are the frameworks and tools that you must be familiar with to be able to contribute to this project:
1. [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference) and [TypeScript](https://www.typescriptlang.org/docs/handbook/intro.html)
2. [Node.js](https://nodejs.org/en/download/) or [Bun](https://bun.sh/) (we personally prefer Bun)
3. [Git](https://git-scm.com/downloads)
4. [React](https://react.dev/learn)
5. [Next.js](https://nextjs.org/learn)
6. [Tailwind CSS](https://tailwindcss.com/docs)
7. [Vercel](https://vercel.com/docs)
8. [Supabase](https://github.com/supabase/supabase)

## Running Locally
1. Run the following in your terminal starting with cloning the repository:
```bash
git clone https://github.com/dlsucomet/verifeye.git
```
2. Install dependencies:
```bash
npm install    # or bun install
```
3. Create a `.env.local` file with the contents of `.env.template` and fill in the keys.

> [!IMPORTANT]
> The project will not run properly without the environment variables. Seek assistance from the project owner if you don't have the necessary values for the variables.

4. Run the development server:
```bash
npm run dev    # or bun dev
```

## Deployment
As of this moment, we are still deciding which platform to use for deployment. Regardless, we will create a pipeline that would automatically deploy the application to the chosen platform whenever a new commit is pushed to the main branch.