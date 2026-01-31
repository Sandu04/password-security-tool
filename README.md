Password Security Tool
Docker tool for generating strong passwords and analyzing password security.

# Generate password
docker run --rm sandu04/password-tool --length 16 --upper --numbers --special

# Analyze password
docker run --rm sandu04/password-tool --check "password123" --show

Features:
-Generate secure passwords with customizable criteria
-Analyze password strength (entropy-based)
-Test against common password lists
-Generate memorable passwords
-Encrypted history storage
-Docker support - runs anywhere

Docker Commands:

# Basic usage
docker run --rm sandu04/password-tool --help

# Examples
docker run --rm sandu04/password-tool --length 20
docker run --rm sandu04/password-tool --memorable --words 3
docker run --rm sandu04/password-tool --batch 5 --length 12

 Links
-GitHub: https://github.com/Sandu04/password-security-tool
-Docker Hub: https://hub.docker.com/r/sandu04/password-tool

Source Code
For local execution:
git clone https://github.com/Sandu04/password-security-tool.git
cd password-security-tool
python3 password_gen.py --help