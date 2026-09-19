# V5.4.1 Deploy Fix

- Ensures `xlsx` is declared as a production dependency.
- Adds `@types/react` and `@types/react-dom` required by `tsc -b` in clean Vercel builds.
- Adds `src/vite-env.d.ts` for `import.meta.env` typing.
- Adds `vercel.json` with Vite build/output settings and SPA fallback rewrite.
