# Bulk-IP
Developed a bulk IP scanner tool capable of scanning thousands of IPs simultaneously, delivering detailed information including geographic location, ISP, organization, and WHOIS data.
# Bulk IP Scanner

![Banner Image](https://example.com/banner-image)

**Bulk IP Scanner** is a powerful, fast, and customizable tool for scanning large sets of IP addresses. Designed with cybersecurity professionals and network administrators in mind, this tool enables effective network mapping and vulnerability assessment.

## Features

- **Concurrent Scanning**: Simultaneously scan thousands of IPs, making it highly efficient.
- **Customizable Port Range**: Specify which ports to scan for precise results.
- **Detailed Output**: Comprehensive results for each IP scanned, including open ports and response times.
- **Interactive UI**: Command-line based interface with color-coded output for clarity.
- **Export Options**: Save results in CSV or JSON formats for further analysis.

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/bulk-ip-scanner.git
   cd bulk-ip-scanner
   ```

2. **Install Dependencies**
   Make sure you have Python 3.x installed, then run:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Basic command structure:
```bash
python bulk_ip_scanner.py -f ips.txt -p 80,443,8080
```
- `-f` : Path to the file containing IP addresses.
- `-p` : Ports to scan, separated by commas.

### Example
Scan IPs listed in `targets.txt` on common web ports (80, 443):
```bash
python bulk_ip_scanner.py -f targets.txt -p 80,443
```

## Output Preview
![Output Example](https://example.com/output-example)

## Contributing
Contributions are welcome! Please submit a pull request or open an issue to suggest improvements.

## License
This project is licensed under the [MIT License](LICENSE).

---

**Stay sharp, stay secure.**

