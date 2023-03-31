# Code Challenge

## Description

This is a solution to the Code Challenge Request 97073 (IS-24 Full Stack Developer Position).

The API part was developed using **Node.js** with **Express.js** and **TypeScript**. The database is a JSON file operated by the library **JSON-SERVER**. The Frontend part was developed in **React.JS** with **Typescript**, using **Vite** and **Tailwind CSS** for stylization. The **Node** version used was the v18.13.0.

## Instructions

### API

After clone the repository, using a terminal in **Visual Studio Code**, inside folder **api** from the repository:

1. Install all dependencies:

```
npm install
```

2. Start Json-Server

```
npm run db
```

3. Start the server (in other terminal instance)

```
npm run dev
```

The API will be available at http://localhost:3000/api/.
The routes available are listed in the documentation: http://localhost:3000/api/api-docs

### Frontend

Using a terminal in **Visual Studio Code**, inside folder **frontend** from the repository:

1. Install all dependencies:

```
npm install
```

2. Start the application

```
npm run dev
```

The web application will be available at http://localhost:5173

At the main page will be available all **products** registered. It is possible to filter the list of products by the name of the _Scrum Master_ or by the name of a _developer_, partial names are accepted. Click in each **Product Number** will display a page containing all the information about that product. The **Edit Product** button is available for each product and it is also possible to add new products using a button at the top right of the list.
