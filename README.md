# To-Do Task Web App

## Overview
This is a simple To-Do task web application built with **Go (Golang) for the backend** and **React for the frontend**. It supports full CRUD (Create, Read, Update, Delete) operations.

## Features
- Add new Todo
- View all Todos
- Edit existing Todos
- Delete a Todo

## Tech Stack
- **Frontend:** React, Vite, TanStack Query
- **Backend:** Golang (using Gin or Fiber)
- **Database:** MongoDB (MongoDB Atlas)
- **API Communication:** REST API

## Getting Started

### Prerequisites
- Go installed (`>=1.18`)
- Node.js and npm/yarn installed

### Backend Setup (Golang)
1. Clone the repository:
   ```sh
   git clone https://github.com/Vickynjoroge/react-go.git
   cd react-go
   ```
2. Install dependencies:
   ```sh
   go mod tidy
   ```
3. Run the server:
   ```sh
   go run main.go
   ```
4. The API should now be running on `http://localhost:8080`.

### Frontend Setup (React)
1. Navigate to the frontend folder:
   ```sh
   cd ../client
   ```
2. Install dependencies:
   ```sh
   npm install
   # or
   yarn install
   ```
3. Start the development server:
   ```sh
   npm run dev
   ```
4. Open the app in the browser at `http://localhost:5173`.

## API Endpoints
| Method | Endpoint       | Description       |
|--------|--------------|------------------|
| GET    | `/todos`     | Get all todos    |
| POST   | `/todos`     | Create a new todo|
| PUT    | `/todos/:id` | Update a task    |
| DELETE | `/todos/:id` | Delete a task    |

## Deployment
For deployment, you can use Railway or other cloud providers.

## License
This project is open-source and available under the [MIT License](LICENSE).

## Author
Victor Ngigi Njoroge

