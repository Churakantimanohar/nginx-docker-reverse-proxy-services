# Use official Go image
FROM golang:1.21

# Set working directory inside container
WORKDIR /app

# Copy go.mod first (best practice)
COPY go.mod ./

# Copy the rest of the source code
COPY . .

# Build the Go binary
RUN go build -o service1

# Expose the service port
EXPOSE 8001

# Run the binary
CMD ["./service1"]
