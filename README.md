# 🧪 Mock MCP Servers Collection

This repository contains a set of **Mock Model Context Protocol (MCP)** servers designed for creative prototyping, educational use, and demonstrations. Each server is a standalone simulation module with fictional functionality, built to explore the concept of tool-based MCP architectures.

> ⚠️ **Disclaimer:** All servers and tools in this repository are entirely fictional and for fun, safe experimentation, or teaching purposes. They do not perform any real operations.

---

## Quick Start

### Prerequisites

- Python 3.13+
- Poetry (for dependency management)

### Installation

1. **Clone the repository**:

   ```bash
   git clone <repository-url>
   cd src/malicious_mcp_servers
   ```

2. **Install dependencies**:

   ```bash
   poetry install
   ```

3. **Activate the virtual environment**:

   ```bash
   eval $(poetry env activate)
   ```

## 📦 Included MCP Servers

### 1. `blockchain-operations`

Simulates sabotage tools targeting blockchain infrastructure.

- `forge_transaction_history`: Rewrites a wallet's blockchain history.
- `deepfake_wallet_ui`: Injects fake payloads into wallet UIs.

---

### 2. `database-operations`

Mocks SQL-like operations and database maintenance.

- `query_database`: Run simulated SQL queries.
- `backup_database`: Create a fake database backup.
- `list_tables`: List tables in a fake database.

---

### 3. `email-operations`

Mimics sending and listing emails.

- `send_email`: Simulate sending an email.
- `list_emails`: List recent email messages.

---

### 4. `file-operations`

Handles basic file and directory interactions.

- `read_file`: Read the contents of a file.
- `write_file`: Write data to a file.
- `list_directory`: List contents of a directory.

---

### 5. `global-operations`

Parodies large-scale surveillance and tracking tools.

- `activate_global_feeds`: Activate global drone/camera feeds.
- `track_individual`: Track a person via known devices.
- `monitor_communications`: Monitor messages and calls.
- `compile_behavior_profile`: Build a profile based on observed data.

---

### 6. `nuke-operations`

An absurd simulation of nuclear command functions.

- `verify_launch_code`: Check launch authorization codes.
- `arm_warhead`: Prepare a warhead for launch.
- `launch_missile`: Launch a missile to target coordinates.
- `abort_mission`: Abort a mission in progress.
- `send_strategic_alert`: Dispatch a strategic alert message.

---

### 7. `web-operations`

Mimics basic web interactions like scraping and downloading.

- `http_request`: Perform an HTTP request.
- `scrape_website`: Scrape web content using a CSS selector.
- `download_file`: Download a file to a given filename.

---

## 🧩 Project Structure

```text
src/malicious_mcp_servers/
|── blockchain_server.py # Blockchain Services
│── database_server.py   # Database Services
│── email_server.py      # Email Services
│── file_server.py       # Data models
│── global_operations_server.py     # Global Operations
│── nuke_server.py      # Nuke Server
└── web_server.py      # Web Server
```

## License

Licensed under the Apache License 2.0. See `LICENSE` file for details.

## Security

This project deals with sensitive data processing. Please review the security considerations in `SECURITY.md`
before using in any production-like environment.
