![Web Sloth Banner](https://github.com/securefeds/web_sloth/banner.png)


# **web_sloth: Multi-Vulnerability Web Scanner**

**web_sloth** is a powerful and versatile vulnerability scanner designed to detect various security issues in web applications, including Local File Inclusion (LFI), Open Redirects (OR), SQL Injection (SQLi), and Cross-Site Scripting (XSS). This tool, developed by **OSPOKS** and **M0SAIF-ANTNET**, is intended for security researchers, developers, and ethical hackers to assess the security of their web applications.

## **Features**

- **LFI Scanner**: Detects vulnerabilities allowing unauthorized access to files on the server.
- **Open Redirect Scanner**: Identifies potential open redirects that could be exploited to direct users to malicious sites.
- **SQL Injection Scanner**: Uncovers weaknesses that may permit attackers to execute arbitrary SQL queries on a database.
- **XSS Scanner**: Locates XSS vulnerabilities that could enable attackers to inject malicious scripts into web pages.
- **Multi-threaded Scanning**: Enhances scanning efficiency by using multiple threads for faster operation.
- **Custom Payloads**: Enables users to provide tailored attack payloads for specific vulnerability types.
- **Custom Success Criteria**: Allows users to define specific conditions for identifying successful exploitation attempts.
- **Command-line Interface (CLI)**: A simple and intuitive CLI for fast and efficient scanning.
- **Vulnerable URL Storage**: Saves vulnerable URLs discovered during the scan for future analysis.

## **System Requirements**

Before using **web_sloth**, ensure the following dependencies are installed:

- **Python 3.x**
- `webdriver_manager==4.0.2`
- `selenium==4.24.0`
- `aiohttp==3.10.5`
- `beautifulsoup4==4.12.3`
- `colorama==0.4.6`
- `rich==12.6.0`
- `requests==2.28.1`

## **Installation Instructions**

Follow these steps to install and set up **web_sloth**:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/secuRefeds/web_sloth.git
   cd web_sloth
   ```

2. **Install the required dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

## **Usage**

To start using **web_sloth**, follow these steps:

1. **Run the tool**:

   ```bash
   python web_sloth.py
   ```

2. **Input options**:
   - **URL Input**: Provide a single URL or a file containing multiple URLs to scan.
   - **Payload Selection**: Choose or supply a custom payload file targeting specific vulnerabilities.
   - **Success Criteria**: Define patterns or indicators that signal a successful exploitation attempt.
   - **Concurrent Threads**: Set the number of threads to control the scanning speed and performance.
   - **Results Output**: View the real-time scan results on the terminal and save the identified vulnerable URLs to a file for further analysis.

## **Customization Options**

**web_sloth** offers several customization features to cater to specific needs:

- **Custom Payloads**: Modify or create your own payloads to target specific vulnerabilities more effectively.
- **Success Criteria**: Customize the success indicators to identify exploitation attempts based on unique error messages or specific responses.
- **Multi-threading**: Adjust the number of threads to improve scanning performance based on the available system resources.

## **Disclaimer**

**web_sloth** is designed for educational and ethical purposes only. Users must have explicit permission to test the security of any web application. Unauthorized scanning or exploitation of third-party systems is illegal and against the ethical principles of cybersecurity.

## **Contributors**

- **OSPOKS**
- **M0SAIF-ANTNET**

## **License**

This project is licensed under the **Apache License 2.0**. See the [LICENSE](LICENSE) file for more information.

