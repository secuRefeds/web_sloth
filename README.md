
# web_sloth: Multi-Vulnerability Scanner

**web_sloth** is a robust and versatile multi-vulnerability scanner designed to identify various web application vulnerabilities, including Local File Inclusion (LFI), Open Redirects (OR), SQL Injection (SQLi), and Cross-Site Scripting (XSS). This tool was developed by **OSPOKS** and **M0SAIF-ANTNET**.

## Features

- **LFI Scanner**: Scans for vulnerabilities that allow unauthorized access to local files on the server.
- **Open Redirect Scanner**: Detects potential open redirect issues that can be exploited to redirect users to malicious sites.
- **SQL Injection Scanner**: Identifies weaknesses that may allow attackers to execute arbitrary SQL queries on the database.
- **XSS Scanner**: Locates vulnerabilities that could enable attackers to inject malicious scripts into web pages.
- **Multi-threaded Scanning**: Boosts scanning efficiency by running multiple processes simultaneously.
- **Custom Payloads**: Enables users to tailor attack payloads to better match the target application’s behavior.
- **Custom Success Criteria**: Allows setting specific indicators to determine successful exploitation based on individual needs.
- **Simple Command-line Interface**: Offers a straightforward and easy-to-use command-line interface for quick operation.
- **Vulnerable URL Storage**: Provides an option to save the URLs found to be vulnerable during the scan for later review.

## Requirements

- **Python 3.x**
- `webdriver_manager==4.0.2`
- `selenium==4.24.0`
- `aiohttp==3.10.5`
- `beautifulsoup4==4.12.3`
- `colorama==0.4.6`
- `rich==12.6.0`
- `requests==2.28.1`

## Installation

### Clone the repository

```bash
git clone https://github.com/OSPOKS/web_sloth.git
cd  web_sloth
```
## Running the Script

To run the script, use the following command:

```bash
python web_sloth.py
```
## Input Information:

- **Input URL/File**: You can provide a single URL or an input file containing a list of URLs to scan.
- **Payload File**: Select or provide a custom payload file for the type of vulnerability you want to scan for.
- **Success Criteria:**:  Define the patterns or strings that indicate a successful exploitation attempt.
- **Concurrent Threads:**: Set the number of threads for multi-threaded scanning.
- **View and Save Results:**: Results will be displayed in real-time as the scan progresses.
After the scan completes, you will have the option to save the URLs found to be vulnerable to a file for future reference.

## Customization

web_sloth allows for various levels of customization to fit your specific testing needs:
- **Custom Payloads:**: Create or modify payload files to suit specific vulnerability types or applications. Payloads should be tailored to the vulnerability being tested.
- **Success Criteria:**: Adjust the success criteria patterns in the tool to identify successful exploitation attempts more accurately. For example, you can modify the tool to check for specific error messages or unique responses.
- **Concurrent Threads:**:  Control the number of concurrent threads used during the scan to optimize performance based on system resources.

## Disclaimer

web_sloth is intended for educational and ethical hacking purposes only. It should only be used to test systems you own or have explicit permission to test. Unauthorized use on third-party websites or systems without consent is illegal and unethical.

## Contributors

 **OSPOKS** 
 **M0SAIF-ANTNET**.
