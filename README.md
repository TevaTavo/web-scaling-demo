# Web Scaling Demo

This project demonstrates a scalable web application using Express, Redis, MongoDB, and Nginx for load balancing.

## Features

- **Express App**: Serves a simple weather application.
- **Redis**: Caches weather data to improve performance.
- **MongoDB**: Logs each request with the request date and requester's IP address.
- **Nginx**: Load balances traffic across multiple instances of the Express app.

## Setup

### Prerequisites

- Docker and Docker Compose installed on your machine.

### Running the Application

1. Clone the repository:
   ```bash
   git clone <your-github-repo-url>
   cd web-scaling-demo
   ```

2. Start the application using Docker Compose:
   ```bash
   docker-compose up
   ```

3. Access the application at `http://localhost`.

## Configuration

- The Express app runs on port 8080.
- Three instances of the app are deployed for horizontal scaling.
- MongoDB logs each request with the request date and requester's IP address.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
