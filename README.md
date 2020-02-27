## Build for production

Visit at:
`localhost:8080`

## Build for production

Build with:
`docker build .`

Run with:
`docker run -p 8080:80 <CONTAINER ID>`


## Development and Testing with Docker

Build with:
`docker build -f Dockerfile.dev .`

Run with:
`docker run -p 3000:3000 -v /app/node_modules -v $(pwd):/app <CONTAINER ID>`