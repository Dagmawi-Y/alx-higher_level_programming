# 0x11. Python - Network #1

## Description
This project focuses on working with network requests in Python using `urllib` and `requests` libraries. It covers making HTTP requests, handling responses, and interacting with web APIs.

## Learning Objectives
- How to fetch internet resources with `urllib`
- How to decode `urllib` body response
- How to use the `requests` library
- How to make HTTP GET, POST, PUT requests
- How to fetch JSON resources
- How to manipulate data from an external service

## Requirements
- Ubuntu 20.04 LTS
- Python 3.8.5
- `pycodestyle` 2.8.*
- All scripts must be executable

## Tasks

### 0. What's my status? #0
- **File:** `0-hbtn_status.py`
- **Description:** Fetches `https://alx-intranet.hbtn.io/status` using `urllib` and displays the body of the response.

### 1. Response header value #0
- **File:** `1-hbtn_header.py`
- **Description:** Takes a URL, sends a request, and displays the value of the `X-Request-Id` variable in the response header using `urllib`.

### 2. POST an email #0
- **File:** `2-post_email.py`
- **Description:** Takes a URL and an email, sends a POST request to the URL with the email as a parameter, and displays the body of the response using `urllib`.

### 3. Error code #0
- **File:** `3-error_code.py`
- **Description:** Takes a URL, sends a request, and displays the body of the response. Handles `urllib.error.HTTPError` exceptions and prints the HTTP status code.

### 4. What's my status? #1
- **File:** `4-hbtn_status.py`
- **Description:** Fetches `https://alx-intranet.hbtn.io/status` using `requests` and displays the body of the response.

### 5. Response header value #1
- **File:** `5-hbtn_header.py`
- **Description:** Takes a URL, sends a request, and displays the value of the `X-Request-Id` variable in the response header using `requests`.

### 6. POST an email #1
- **File:** `6-post_email.py`
- **Description:** Takes a URL and an email address, sends a POST request to the URL with the email as a parameter, and displays the body of the response using `requests`.

### 7. Error code #1
- **File:** `7-error_code.py`
- **Description:** Takes a URL, sends a request, and displays the body of the response. Prints the HTTP status code if the status is greater than or equal to 400 using `requests`.

### 8. Search API
- **File:** `8-json_api.py`
- **Description:** Takes a letter, sends a POST request to `http://0.0.0.0:5000/search_user` with the letter as a parameter, and displays the response.

### 9. My GitHub!
- **File:** `10-my_github.py`
- **Description:** Takes GitHub credentials (username and personal access token), uses the GitHub API to display the user ID using `requests`.

### 10. Time for an interview!
- **File:** `100-github_commits.py`
- **Description:** Lists the 10 most recent commits of the `rails` repository by the user `rails`. Displays commits as `<sha>: <author name>` using the GitHub API.

## Repository
- **GitHub repository:** `alx-higher_level_programming`
- **Directory:** `0x11-python-network_1`
