Prisma Setup Commands

1. Install Prisma
   npm install -D prisma@6.1.0
   npm install @prisma/client@6.1.0
2. Initialize Prisma
   npx prisma init
3. Configure the Prisma Schema

Edit the following file:

prisma/schema.prisma 4. Push the Database Schema
npx prisma db push 5. Generate the Prisma Client
npx prisma generate

Run npx prisma generate whenever you make changes to prisma/schema.prisma.
