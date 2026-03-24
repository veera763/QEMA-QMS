# QEMA QMS (Quality Engineering Management System)
Enterprise-level Quality Management System (QMS) built with Python, Linux &amp; Windows integration. Supports file upload, distributed processing, automation workflows, and real-time monitoring for production environments.

## Features
- File Upload via Django Web App
- Distributed Worker Processing (Windows)
- Automatic PDF Conversion
- Backup Storage System

## Tech Stack
- Linux (AlmaLinux 9.7)
- Django + Apache
- Windows Worker (Python)
- Paramiko (SFTP)
- Watchdog
- FPDF

## Architecture
User → Upload → Linux Server → Windows Worker → PDF → Backup

## Setup Instructions
Refer /linux-server and /windows-worker folders

## Future Improvements
- Queue System (RabbitMQ)
- Docker Deployment
- Logging & Monitoring
