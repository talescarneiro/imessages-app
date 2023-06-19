# IMessages App

Brief project description.

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