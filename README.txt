# 404 Discord Token Logger

## Description

**404 Discord Token Logger** is a Python script designed to extract Discord tokens and gather system information from a user, sending the data to a specified Discord webhook.

> **Disclaimer**: This tool is for **educational purposes only**. Unauthorized use or distribution of this tool may violate Discord's terms of service and local cybersecurity laws. Ensure you have permission before using tools like this.

---

## How It Works

1. **Token Extraction**:
    - The script scans the user's local Discord files to locate potential tokens using a regular expression.
  
2. **Token Validation**:
    - Each found token is validated by making a request to Discord's API to check its authenticity.

3. **Information Sent**:
    - The script sends the tokens along with system information (OS, machine name, processor, etc.) to the specified Discord webhook.

---

## Setup Instructions

### 1. Create a Discord Webhook

- Set up a webhook in any Discord server where you want to receive the token and system information.

### 2. Update the Webhook URL

- Open the script and replace the following line:

    ```python
    WEBHOOK = "YOUR DISCORD WEBHOOK HERE"
    ```

- Replace `"YOUR DISCORD WEBHOOK HERE"` with your actual webhook URL.

### 3. Send the Script

- After making changes, send the script to the target user. When they run the script, it will:
    - Collect any found Discord tokens.
    - Validate the tokens using Discord's API.
    - Send the valid tokens and system info to your Discord webhook.

---

## System Information Sent

The script gathers and sends the following system details:

- Operating System (OS)
- PC Name
- OS Version
- Machine Type
- Processor Information

---

## Features

- Extracts and validates Discord tokens.
- Sends valid tokens and system information to a Discord webhook.
- Includes a notification to `@everyone` in the Discord channel when data is received.

---

## Author

- **Y2K (icmad_y2k)**
- 404 Discord Token Logger

---

## License

This project is for **educational purposes only**. Unauthorized use may result in penalties according to local laws and the terms of service of platforms like Discord.
