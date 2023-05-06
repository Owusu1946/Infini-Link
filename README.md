# Full Stack Airbnb Clone with Next.js 13 App Router: React, Tailwind, Prisma, MongoDB, NextAuth 2023

![Copy of Fullstack Twitter Clone (8)](https://user-images.githubusercontent.com/23248726/229031522-64a49ad0-66f7-4ea8-94a8-f64a0bb56736.png)


This is a repository for a Full Stack Airbnb Clone with Next.js 13 App Router: React, Tailwind, Prisma, MongoDB, NextAuth.

[VIDEO TUTORIAL](https://youtu.be/c_-b_isI4vg)

Master the art of building a real-time Messenger clone using the latest web development technologies. In this comprehensive tutorial, we'll walk you through the process of creating a fully-functional and visually stunning chat application that rivals the best in the industry.

Key Features:

Next.js 13 framework using App Router for efficient routing and dynamic page rendering
React for creating reusable components
TailwindCSS and Headless UI for modern and sleek design
Prisma and MongoDB for a robust and scalable database solution
NextAuth for secure authentication and social logins with Google and Github
Real-time messaging and notifications using Pusher
Efficient form handling with react-hook-form
Throughout this tutorial, you'll gain hands-on experience in building a state-of-the-art chat application from scratch. We'll cover everything from setting up Next.js 13 and React to managing authentication with NextAuth and social logins. We'll also dive into using TailwindCSS and Headless UI to create an eye-catching design, while exploring real-time messaging and notifications with Pusher.

Whether you're an experienced developer looking to expand your skillset or a beginner eager to learn the latest web development technologies, this tutorial has something for everyone. Join us on this exciting journey and take your web development skills to new heights!


### Prerequisites

**Node version 14.x**

### Cloning the repository

```shell
git clone https://github.com/AntonioErdeljac/next13-messenger.git
```

### Install packages

```shell
npm i
```

### Setup .env file


```js
DATABASE_URL=
NEXTAUTH_SECRET=

NEXT_PUBLIC_PUSHER_APP_KEY=
PUSHER_APP_ID=
PUSHER_SECRET=

NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=

GITHUB_ID=
GITHUB_SECRET=

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
```

### Setup Prisma

```shell
npx prisma db push

```

### Start the app

```shell
npm run dev
```

## Available commands

Running commands with npm `npm run [command]`

| command         | description                              |
| :-------------- | :--------------------------------------- |
| `dev`           | Starts a development instance of the app |
