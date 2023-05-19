# E2E TYPE SAFE GRAPHQL - SERVER

---

## Simple end-to-end type safe graphql-react app, this one being the graphql server.

---

### Setup:

1. Install dependencies with npm or yarn.
2. Then create a .env file with your postgres url, in my example I use postgres on [railway](https://railway.app/).
3. Run `npx prisma migrate dev --name init` to run create and apply the migration to your database.
4. Run `npx prisma db seed` to seed your database with mock data.
5. Run `npm run build` to generate Prisma Client and Pothos output types.
6. Locally, run `npm run dev`.
