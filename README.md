# Prisma Setup Guide

## 1. Install Prisma

```bash
npm install -D prisma@6.1.0
npm install @prisma/client@6.1.0
```

## 2. Initialize Prisma

```bash
npx prisma init
```

## 3. Configure Prisma Schema

Edit the Prisma schema file:

```text
prisma/schema.prisma
```

Add your database connection and models as needed.

## 4. Generate Prisma Client

```bash
npx prisma generate
```

## 5. Push Schema to Database

```bash
npx prisma db push
```

## 6. Regenerate Prisma Client (After Schema Changes)

```bash
npx prisma generate
```
