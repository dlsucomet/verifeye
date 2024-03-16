# VerifEye
A verifiability tool for social media platforms that serves short-form video content. This is a research project submitted to the DLSU Center for Complexity and Emerging Technologies.

## Prerequisites
The following are the frameworks and tools that you must be familiar with to be able to contribute to this project:
1. [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference) and [TypeScript](https://www.typescriptlang.org/docs/handbook/intro.html)
2. [Node.js](https://nodejs.org/en/download/) or [Bun](https://bun.sh/) (we personally prefer Bun)
3. [React](https://react.dev/learn)
4. [Next.js](https://nextjs.org/learn)
5. [Tailwind CSS](https://tailwindcss.com/docs)

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
Once changes have been made, you can push commits to the `main` branch and the GitHub Actions will automatically deploy the changes to production. You can view the deployed web application at https://comet.dlsu.edu.ph/verifeye.