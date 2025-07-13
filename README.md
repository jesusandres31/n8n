# n8n Containerized Setup

This project provides a containerized setup for [n8n](https://n8n.io/), an extendable workflow automation tool, using Docker Compose.

## Prerequisites

- [Docker](https://www.docker.com/get-started) installed
- [Docker Compose](https://docs.docker.com/compose/install/) installed

## Getting Started

1. **Clone this repository** (if you haven't already):

   ```sh
   git clone https://github.com/jesusandres31/n8n
   cd n8n
   ```

2. **Start n8n using Docker Compose:**

   ```sh
   docker-compose up -d
   ```

   This will pull the latest n8n image and start the service in detached mode.

3. **Access the n8n UI:**
   - Open your browser and go to: [http://localhost:5678](http://localhost:5678)

## Configuration

- You can customize environment variables and volumes in the `docker-compose.yml` file to persist data and configure n8n as needed.
- For production deployments, consider setting up authentication and HTTPS. See the [n8n documentation](https://docs.n8n.io/hosting/docker/) for more details.

## Useful Commands

- **Stop the containers:**
  ```sh
  docker-compose down
  ```
- **View logs:**
  ```sh
  docker-compose logs -f
  ```

## References

- [n8n Documentation](https://docs.n8n.io/)
- [n8n Docker Guide](https://docs.n8n.io/hosting/docker/)

---

Feel free to modify this README to fit your specific configuration or deployment needs.

---
