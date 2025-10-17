# Nginx Log Analyzer

A simple shell script to analyze Nginx access log files and display the top 5 most frequent entries for IP addresses, requested paths, HTTP status codes, and user agents.

## Features

- Top 5 IP addresses with the most requests
- Top 5 most requested paths
- Top 5 response status codes
- Top 5 user agents

## Requirements

- Linux or macOS terminal
- Bash shell
- Basic Unix utilities: `awk`, `sort`, `uniq`, `head`

## Setup

1. Clone this repository or download the script.
2. Place your Nginx log file in the same directory and name it `nginxLogFile` (or update the script to match your log filename).
