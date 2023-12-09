# HTTP Bruteforce Script

## Overview

`http_bruteforce.py` is a simple Python script designed for HTTP brute-force attacks. It allows users to perform username and password combinations against a target URL using either GET or POST requests. The script supports customizing the username and password parameters, choosing the HTTP method, and specifying an optional error message to identify invalid attempts.

## Features

- **HTTP Methods:** Supports both GET and POST methods.
- **User-defined Parameters:** Allows users to specify the username and password parameters.
- **Error Handling:** Optionally handles error messages to differentiate between valid and invalid login attempts.
- **Wordlist Support:** Utilizes external wordlists for usernames and passwords.
- **Colorful Output:** Provides a visually appealing and informative console output.

## Prerequisites

Ensure you have the following prerequisites installed before using the script:

- Python 3.x
- `requests` library (`pip install requests`)
- `termcolor` library (`pip install termcolor`)

## Usage

```bash
python http_bruteforce.py -x <usr_wordlist> -y <pwd_wordlist> -t <target_url> -u <username_param> -p <password_param> -m <http_method> [-e <error_message>]
