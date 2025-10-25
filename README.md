cat <<EOL > README.md
# Docker Compose Cricket App

This repository contains a **Node.js** cricket application set up with **Docker Compose** and **MySQL**.

## Project Structure

\`\`\`
cricket-app/
├── app.js
├── Dockerfile
├── docker-compose.yml
├── package.json
├── public/
└── README.md
\`\`\`

## Features

- Node.js backend for cricket data
- MySQL database integration
- Dockerized app for easy deployment
- Docker Compose setup to run both app and database together

## Prerequisites

- Docker
- Docker Compose
- Node.js (for local development, optional if using Docker)

## How to Run

1. Clone the repository:

\`\`\`bash
git clone https://github.com/darshan-bs-2005/docker-compose.git
cd docker-compose
\`\`\`

2. Build and run the containers:

\`\`\`bash
docker-compose up --build
\`\`\`

3. Access the app at:

\`\`\`
http://localhost:3000
\`\`\`

4. To stop the containers:

\`\`\`bash
docker-compose down
\`\`\`

## Database

- MySQL is used as the database.
- Default credentials (from docker-compose.yml):

\`\`\`
Username: root
Password: darshan
Database: cricket_db
\`\`\`

## Contributing

Feel free to open issues or submit pull requests.

## License

MIT License
EOL
