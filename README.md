# Demo-Project: TODO LIST App

## Demo

http://localhost:3000

## Running

First, run:

```sh
npm install
```

To run the webpack dev server:

```sh
npm start
```

To compile everything:

```sh
npm run build
```

## System Requirements

- [Node.js 14+](https://nodejs.org/en/download/)

## API documents

| No. | Method | URL                             | Body               | Note              |
| --- | ------ | ------------------------------- | ------------------ | ----------------- |
| 1   | GET    | http://localhost:3000/todos     |                    | Get list todos    |
| 2   | GET    | http://localhost:3000/todos/:id |                    | Get todo          |
| 3   | POST   | http://localhost:3000/todos     | ["text": required] | Create todo       |
| 4   | PATCH  | http://localhost:3000/todos/:id | ["text": required] | Update todo by id |
| 5   | DELETE | http://localhost:3000/todos/:id |                    | Delete todo by id |

## Auth

- duc.bui
- ducbui.dev@gmail.com
