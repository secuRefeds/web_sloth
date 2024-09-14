Here's a refined version of your `README.md` file:

---

# **web_sloth: Multi-Vulnerability Web Scanner**

**web_sloth** is a comprehensive multi-vulnerability scanner designed to detect a wide range of web application vulnerabilities, such as Local File Inclusion (LFI), Open Redirects (OR), SQL Injection (SQLi), and Cross-Site Scripting (XSS). This tool was created by **OSPOKS** and **M0SAIF-ANTNET** for security researchers and ethical hackers.

## **Features**

- **LFI Scanner**: Detects vulnerabilities that allow unauthorized access to server files.
- **Open Redirect Scanner**: Finds potential open redirects that could redirect users to malicious sites.
- **SQL Injection Scanner**: Identifies weaknesses that allow arbitrary SQL queries on the database.
- **XSS Scanner**: Locates XSS vulnerabilities that enable malicious script injection.
- **Multi-threaded Scanning**: Enhances performance by running scans across multiple threads.
- **Custom Payloads**: Supports tailored payloads for different application behaviors.
- **Custom Success Criteria**: Allows definition of success markers for precise exploitation detection.
- **Simple CLI**: Easy-to-use command-line interface for quick and efficient scans.
- **Vulnerable URL Storage**: Option to save identified vulnerable URLs for future analysis.

## **Requirements**

- **Python 3.x**
- `webdriver_manager==4.0.2`
- `selenium==4.24.0`
- `aiohttp==3.10.5`
- `beautifulsoup4==4.12.3`
- `colorama==0.4.6`
- `rich==12.6.0`
- `requests==2.28.1`

## **Installation**

### Clone the Repository

```bash
git clone https://github.com/secuRefeds/web_sloth.git
cd web_sloth
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

## **Usage**

To start scanning, use the following command:

```bash
python web_sloth.py
```

### Input Options:

- **URL/File Input**: Provide either a single URL or a file containing multiple URLs to scan.
- **Custom Payload File**: Supply a custom payload file for the type of vulnerability you wish to test.
- **Success Criteria**: Define patterns or strings that indicate a successful exploitation attempt.
- **Threading**: Specify the number of threads for multi-threaded scanning.
- **Real-time Results & Saving**: Results will display in real-time, with the option to save vulnerable URLs to a file.

## **Customization**

**web_sloth** offers flexibility for advanced users:
- **Custom Payloads**: Modify or create payloads to target specific vulnerabilities.
- **Success Criteria**: Adjust success patterns to match error messages or custom responses.
- **Thread Control**: Customize the number of concurrent threads based on system capacity for optimized performance.

## **Disclaimer**

**web_sloth** is intended solely for educational purposes and ethical hacking. Use it only on systems you own or have explicit permission to test. Unauthorized usage is illegal and unethical.

## **Contributors**

- **OSPOKS**
- **M0SAIF-ANTNET**

---
