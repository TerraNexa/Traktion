# Traktion

This is the web application for the Traktion app, where you can check-in with your friends to document your progress and stay motivated.

## Installation

Ensure that you have the lastest version of Node.js installed on your machine.

You can verify the version by running the following commands

```
node -v
```

```
npm -v
```

Next close the project

```
git clone git@github.com:TerraNexa/Traktion.git
```

Afterwards you can initialize the project by installing are the required dependencies

```
npm install
```

## Run Locally

To start the server run the following command

```
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

If you would like the app to run on a different port you can pass the port argument to the command

```
npm run dev -- -p 3005
```

## Contributing

All reusable components should be added to the `src/components` directory. It has already been populated with components provided by the [Catalyst UI Kit](https://catalyst.tailwindui.com/docs).

Layout and Page components components shall be added to the `src/app` directory. Please take a look at the [Next.js docs](https://nextjs.org/docs/app/getting-started/layouts-and-pages) to learn the difference between Layout and Page components and how to create each one.
