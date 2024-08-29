# 0x03. Log Parsing

This project involves parsing web server logs in real-time to compute metrics such as total file size and the count of different HTTP status codes. The script is designed to read from standard input (`stdin`) and handle real-time data streams efficiently.

## Project Overview

The goal of this project is to create a Python script that continuously reads log entries from standard input, parses the relevant data (status codes and file sizes), and computes various metrics:

- **Total file size**: The cumulative size of all files requested in the logs.
- **Number of lines by status code**: The number of times each HTTP status code appears in the log.

The script outputs these metrics after every 10 lines are processed and upon receiving a keyboard interrupt signal (CTRL + C).

## Requirements

- Python 3.x
- The script must be executable.
- The script should conform to PEP 8 style guidelines.
- The script must handle unexpected input gracefully.

## File Structure

- `0-stats.py`: The main Python script that reads from `stdin`, parses log entries, and computes metrics.
- `README.md`: This file, providing an overview and instructions for the project.

## Usage

To run the script, you can use it in conjunction with a log generator or manually input log entries in the specified format:



