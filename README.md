# Secure DevOps Project

## Project Overview
This project demonstrates secure web application deployment using Nginx, HTTPS, TLS, and a Python HTTP server.

## Architecture
Browser → Nginx (HTTPS/TLS) → Python Backend → HTML Application

## Technologies Used
- Linux (Ubuntu)
- Nginx
- Python
- OpenSSL
- HTTPS / TLS
- Git and GitHub

## Features
- Nginx reverse proxy
- HTTPS configuration using a self-signed TLS certificate
- HTTP to HTTPS redirection
- Security response headers
- Backend health and failure testing

## Local Testing
The Python backend runs on:

http://127.0.0.1:9001

The Nginx HTTPS server runs on:

https://localhost:8443

## Note
This is a learning project. The self-signed certificate is intended for local testing only. Private keys and certificates are not included in this repository.
