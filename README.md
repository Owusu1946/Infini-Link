# Real-Time Messenger Clone: Next.js 13, React, Tailwind, Prisma, MongoDB, NextAuth, Pusher (2023)

![Copy of Copy of Fullstack Twitter Clone (1)](https://user-images.githubusercontent.com/23248726/236631198-90414da5-ee43-46a9-8898-70b003bcd83d.png)


This is a repository for a Real-Time Messenger Clone: Next.js 13, React, Tailwind, Prisma, MongoDB, NextAuth, Pusher.

[VIDEO TUTORIAL](https://www.youtube.com/watch?v=PGPGcKBpAk8)

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
