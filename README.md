# Rust Links Fetcher

This is a basic Rust program that fetches and prints all the links from a given URL. It uses the `reqwest` crate for making HTTP requests and the `select` crate for parsing the HTML and extracting the links.

## Dependencies

The following dependencies are required:

- `error-chain` for error handling
- `reqwest` for making HTTP requests
- `tokio` for asynchronous runtime
- `select` for HTML parsing
