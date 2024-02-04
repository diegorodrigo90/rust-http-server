# Simple HTTP Server in Rust

This is a simple HTTP server implemented in Rust with the study purpose only. It serves static files from a specified directory and handles basic HTTP requests.

## Features

* Listens for incoming connections on a specified port
* Handles HTTP GET requests
* Serves static files (HTML, CSS, JavaScript, etc.)
* Returns a 404 response for files not found

## Prerequisites

* Rust programming language installed on your system
* Basic understanding of Rust programming concepts

## Usage

Clone the repository to your local machine:

```bash
git clone https://github.com/your-username/your-repository.git
```

Navigate to the project directory:

```bash
cd your-repository
```

Run the project using Cargo:

```bash
cargo run
```

You can modify the html files in `/www` folder (or in path that you specify in `ROOT_DIR` const).

Access the server in your web browser at `http://127.0.0.1:8477`

## Configuration

You can configure the server by modifying the constants in the `main.rs` file:

* **HOST:** The host address the server will listen on
* **PORT:** The port number the server will listen on
* **ROOT_DIR:** The directory from which the server will serve static files

## License

This project is licensed under the MIT License.
