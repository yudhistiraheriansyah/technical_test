**Vulnerability Scanner**

This Python script is designed to identify security vulnerabilities in web applications, specifically targeting Cross-Site Scripting (XSS) and SQL Injection (SQLi). Users can choose between scanning for XSS or SQLi vulnerabilities.

Instructions for Running the Script

Prerequisites

Python 3.x installed on your system.

Required Python packages can be installed using the following command:

pip install requests beautifulsoup4

Usage

Clone the Repository:

git clone https://github.com/yudhistiraheriansyah/technical_test.git

Navigate to the Project Directory:

cd vulnerability-scanner

Run the Script:

Execute the script by running the following command:

python vulnerability_scanner.py

Enter Target URL:

You will be prompted to enter the target URL of the web application.

Choose Scan Type:

Enter 1 for XSS scanning or 2 for SQL Injection scanning.

For XSS Scanning:

If you chose XSS scanning, you will be prompted to enter JavaScript code for scanning.

Review Results:

The script will provide feedback on the presence of vulnerabilities based on the chosen scan type.

Important Note

Please use this script responsibly and only on web applications that you have permission to test.
The success of the scan depends on the accuracy of payloads and the security context of the target web application.
