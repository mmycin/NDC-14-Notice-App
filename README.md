# NDC-14 Notice App

The **NDC-14 Notice App** is a web application designed to display and manage notices for Notre Dame College. This app is built with a modern tech stack that ensures performance, scalability, and ease of use for both developers and users.

## Tech Stack

### Backend
- **Language**: Golang
- **Web Framework**: Gin
- **DB Framework**: [Mongorm](https://github.com/mmycin/mongorm) (Custom ORM built for MongoDB)

### Database
- **NoSQL Database**: MongoDB

### Frontend
- **Language**: JavaScript
- **Runtime**: Bun
- **UI Library**: Preact JS
- **Styling**: Tailwind CSS

### Network
- **Request Handling**: Fetch API
- **Library**: Axios JS

### Additional Tools
- **Version Control**: Git & GitHub
- **Management**: Forestadmin
- **Deployment**: Onerender
- **Database Management**: MongoDB Atlas & Compass

---

## Website Structure

1. **Home Page**: Displays the latest notices in a clean and responsive layout. The user can scroll through and see updates from NDC.

2. **Admin Dashboard**: Managed via **Forestadmin**, this is where notices can be added, updated, or deleted.

3. **Authentication**: The backend handles authentication and ensures only authorized users can access admin features.

4. **Database Connection**: The app uses **Mongorm**, a custom MongoDB ORM package built in Go, for database operations. The database is hosted on **MongoDB Atlas** and managed with **MongoDB Compass** for local monitoring.

5. **API Layer**: Built with the **Gin** framework, the API layer is responsible for handling requests, fetching notices from the database, and sending them to the frontend.

6. **Frontend**: The UI is built with **Preact JS**, leveraging the **Bun runtime** for optimal performance. **Tailwind CSS** ensures the design is responsive and visually appealing.

7. **Requests**: The frontend communicates with the backend via **Fetch API** and **Axios JS**, ensuring seamless data flow and interaction between the client and server.

---

## How to Run

### Prerequisites:
- Go installed on your system
- Bun runtime installed for frontend
- MongoDB Atlas or a local MongoDB instance

### Backend:
1. Clone the repository.
2. Install dependencies using:
   ```bash
   go mod tidy
   ```
3. Set up environment variables for MongoDB connection.
4. Run the backend using:
   ```bash
   go run main.go
   ```

### Frontend:
1. Navigate to the frontend directory.
2. Install dependencies using Bun:
   ```bash
   bun install
   ```
3. Run the frontend with:
   ```bash
   bun dev
   ```

### Deployment:
The app is deployed using **Onerender**, and you can access the live version once the deployment process completes.

---

## Contributing

If you'd like to contribute, feel free to fork the repository, make changes, and submit a pull request. Contributions are welcome!

---

Happy coding! 🎉

