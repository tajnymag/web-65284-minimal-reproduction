# WEB-65284 - Minimal reproduction

## Steps to reproduce
1. Open the project in WebStorm IDE
2. Install the dependencies with `pnpm install`
3. Generate prisma client with `pnpm prisma generate`
4. Open the `src/main.ts` file
5. Hover over `{ where: { firstName: 'John' } }` argument (lines 6-8) of `prisma.user.findMany` method call
