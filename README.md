# HTTP Bruteforce Script


![App Screenshot](https://github.com/mdaseem03/http_bruteforce/blob/main/img/app-screenshot.png)

## License 
[MIT License](https://choosealicense.com/licenses/mit/)


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
python3 http_bruteforce.py -x <usr_wordlist> -y <pwd_wordlist> -t <target_url> -u <username_param> -p <password_param> -m <http_method> [-e <error_message>]
```

## Help Menu
![Help Message](https://github.com/mdaseem03/http_bruteforce/blob/main/img/help.png)
- `x, --usrwordlist`: Path to the usernames wordlist file (required).
- `y, --pwdwordlist`: Path to the passwords wordlist file (required).
- `t, --target`: Target URL (required).
- `u, --username`: Username parameter (required).
- `p, --password`: Password parameter (required).
- `m, --method`: HTTP method (choose from 'get' or 'post', required).
- `e, --error`: Error message (optional).

## Python Module Installation
[PyPi Module Link](https://pypi.org/project/http-bruteforce/1.0/)
```bash
pip install http_bruteforce
```

## Disclaimer
This script is intended for educational and ethical purposes only. Unauthorized use of this script to perform malicious activities is strictly prohibited. The developers are not responsible for any misuse or damage caused by this script.

## Version History
`v1.0`: Bruteforce credentials in websites with error message using GET and POST methods.

## Author
[@mdaseem03](https://www.linkedin.com/in/mohammed-aseem%F0%9F%8E%96-11baa6217/)
