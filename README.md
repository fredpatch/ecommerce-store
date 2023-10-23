<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="https://i.imgur.com/6wj0hh6.jpg" alt="Project logo"></a>
</p>

<h3 align="center">Full Stack E-commerce + Dashboard Web Application</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/pulls)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center"> E-commerce personal project. The purpose of this short project was to get familiar with new gen coding language, and other dependable framework such as Clerk, or Prisma, and Next.js.

I found it interesting to test new tech and with the many content I find on youtube, i am never out of ideas.
I am also a big fan of the new gen coding language, and i am always looking for new tech to learn and test.

    <br>

</p>

## 📝 Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Deployment](#deployment)
- [Usage](#usage)
- [Built Using](#built_using)
- [TODO](../TODO.md)
- [Contributing](../CONTRIBUTING.md)
- [Authors](#authors)
- [Acknowledgments](#acknowledgement)

## 🧐 About <a name = "about"></a>

Main features that could be implemented:

- Shadcn UI for the Admin!
- Admin and API!
- Possibility to control multiple vendors / stores through one Dashboard(For example you can have a "Shoe store" and a "Laptop store" and a "Suit store", and our CMS will generate API routes for all of those individually!)
- create, update and delete categories!
- create, update and delete products!
- upload multiple images for products, and change them whenever you want!
- create, update and delete filters such as "Color" and "Size", and then match them in the "Product" creation form.
- create, update and delete "Billboards" which are these big texts on top of the page.
- Search through all categories, products, sizes, colors, billboards with included pagination!
- control which products are "featured" so they show on the homepage!
- See your orders, sales, etc.
- See graphs of your revenue etc.
- Clerk Authentication!
- Order creation
- Stripe checkout
- Stripe webhooks
- Supabase + Prisma

## 🏁 Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See [deployment](https://ecommerce-store-ebon-gamma.vercel.app) for the project on a live system.

### Prerequisites

Node 14.x

### Clone the repository

```
https://github.com/fredpatch/ecommerce-store.git
```

### Install packages

```
npm i
```

### Setup .env file

```
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

# This was inserted by `prisma init`:
# Environment variables declared in this file are automatically made available to Prisma.
# See the documentation for more detail: https://pris.ly/d/prisma-schema#accessing-environment-variables-from-the-schema

# Prisma supports the native connection string format for PostgreSQL, MySQL, SQLite, SQL Server, MongoDB and CockroachDB.
# See the documentation for all the connection string options: https://pris.ly/d/connection-strings

DATABASE_URL=''
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=""
STRIPE_API_KEY=
FRONTEND_STORE_URL=http://localhost:3001
STRIPE_WEBHOOK_SECRET=
```

### Connect to Supabase and Push Prisma

```
npx prisma generate
npx prisma db push
```

## 🔧 Start the app <a name = "tests"></a>

```
npm run dev
```

## 🚀 Deployment <a name = "deployment">

</a>

Add additional notes about how to deploy this on a live system.

## ⛏️ Built Using <a name = "built_using"></a>

- [Supabase](https://supabase.com) - Database
- [Prisma](https://www.prisma.io) - Framework
- [Transcript](https://www.typescriptlang.org) - Programming language
- [NodeJs](https://nodejs.org/en/) - Server Environment
- [NextJs](https://nextjs.org) - Web Framework

## 🎉 Acknowledgements <a name = "acknowledgement"></a>

- Hat tip to anyone whose code was used
- Code With Antonio (youtube Channel)
