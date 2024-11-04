# File-Sharing-System

This project involves creating a local HTTP server in Python that can be accessed over the internet through ngrok tunneling. By setting up a server on port 8010, the project allows for remote access to files on the local system. An ngrok tunnel is automatically generated, and a corresponding QR code for the public URL is created to make access even easier. This QR code is saved as an SVG file and launched in the default web browser, allowing users to scan and connect directly to the server from any device.

Key aspects include:

Automation: From server setup to QR code generation and display, the process is fully automated, providing a user-friendly way to access the server remotely.

Technologies Used: The project utilizes Python’s HTTP server modules for hosting, pyngrok for tunneling, and pyqrcode for generating easy-access QR codes.

Use Case: This setup is ideal for quick, temporary sharing of files or web-based content from a local machine to remote users without manual configuration.
