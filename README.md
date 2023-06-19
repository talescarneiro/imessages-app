# IMessages App

The IMessage project is a study-focused application built with Next.js. It is a real-time messaging application that incorporates authentication features.


## Demo
```
https://imessages-app.vercel.app/
```

## Technologies Used

**TypeScript:** The project is developed using TypeScript, a statically typed superset of JavaScript, which provides enhanced tooling and type safety.

**React.js:** The UI components are built using React.js, a popular JavaScript library for building user interfaces.

**Next.js:** Next.js, a framework built on top of React, is used for server-side rendering (SSR) and creating optimized web applications.

**NextAuth:** NextAuth is utilized for authentication, making it easy to implement secure user authentication flows in the project.

**Tailwind CSS:** Tailwind CSS is employed for styling the components. It is a utility-first CSS framework that provides pre-defined utility classes.

**Axios:** Axios is used as an HTTP client for making API requests to external services and fetching data.

**Pusher:** Pusher is utilized for real-time communication, enabling features like instant messaging and real-time updates.

## Prerequisites

```
- Node.js (version 14.x)
```

Make sure you have Node.js installed by running the following command in the terminal:
```
node --version
```

## Cloning the repository

```
git clone git@github.com:talescarneiro/messenger-app.git
```

## Install packages

```
npm install
```

## Setup .env file

```
DATABASE_URL=
NEXTAUTH_SECRET=

GITHUB_ID=
GITHUB_SECRET=

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=

NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=

NEXT_PUBLIC_PUSHER_APP_KEY=
PUSHER_APP_ID=
PUSHER_SECRET=
```

## Setup Prisma

```
npx prisma db push
```

## Run the application

```
npm run dev
```