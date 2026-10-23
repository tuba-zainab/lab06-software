# Lab 06 Challenge: Install It Yourself

## 1. Install and run htop

Command: `sudo apt install -y htop`

Run command: `htop`

Answer: htop displays CPU usage, memory usage, and running processes.

## 2. Find the apache2 version without installing it

Command: `apt show apache2 | grep -E '^(Package|Version):'`

Answer: The available apache2 version is 2.4.66-2ubuntu2.6. Apache2 was not installed.

## 3. Count installed packages

Command: `apt list --installed | wc -l`

Answer: The command returned 854.

## 4. Run Alpine Linux in Docker

Command: `sudo docker run --rm alpine echo "Hello from Alpine"`

Output: Hello from Alpine

## 5. Docker file paths

Command: `ls -l /etc/apt/keyrings/docker.asc`

Answer: /etc/apt/keyrings/docker.asc

Command: `ls -l /etc/apt/sources.list.d/docker.sources`

Answer: /etc/apt/sources.list.d/docker.sources

## 6. Remove htop and verify

Command: `sudo apt remove -y htop`

Verification: `hash -r` followed by `htop`

Answer: The htop command is no longer available after its removal.
