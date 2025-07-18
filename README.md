# TCP-Chat server

A simple chat-server using TCP socket with transport layer security(TLS).

## Getting Started

**1. Prerequisites:**
  
- [OpenSSL](https://www.openssl.org/) installed.
- [Go](https://go.dev/doc/install) installed.
- You also need a [tcp-chat client](https://github.com/AnhTTx13/tcp-chat) as a user interface.

**2. Install the repository:**
  
  ```sh
    go install github.com/AnhTTx13/tcp-chat-server
  ```

## Usage
  
  ```sh
    tcp-chat-server [flag]
  ```

**Flags:**

- `--port [string]`: Specify the port number (default 8080).

**Note:** You must setup SSL certificates the first time you run the app.
