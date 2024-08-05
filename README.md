# Install Go

# Start the app fontend [ the main file is inside ]
- go run ./cmd/web

# Create a module called 'broker'
- cd broker-service
- go mod init broker

# install rooting package to service 'broker'
- cd broker-service
- go get github.com/go-chi/chi/v5
- go get github.com/go-chi/chi/v5/middleware
- go get github.com/go-chi/cors (security package)