# Go API Starter

This starter provides a clean, opinionated structure with essential helpers to read/write JSON, centralized error responses, rate limiting, CORS, panic recovery, graceful shutdown, and tooling to get new projects running quickly.

## 🚀 Getting Started

```bash
# replace with your module path (also update the module path in `cmd/api/main.go`)
go mod init github.com/anujkutal/go-api-starter

# edit .envrc with your configuration
cp .envrc.example .envrc

# install dependencies
make tidy

# start development server
make run/api

# open a new terminal window and send request to server
curl -i localhost:4000/v1/status
```

## 📄 License

[MIT](./LICENSE)
