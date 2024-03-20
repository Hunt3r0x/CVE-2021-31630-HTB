## CVE-2021-31630 Exploit
CVE-2021-31630 Exploit PoC for OpenPLC on WifineticTwo box (Hack The Box),
This script serves as a Proof of Concept (PoC) exploit for CVE-2021-31630, targeting the OpenPLC service running on the WifineticTwo box on the Hack The Box platform. 

## Usage

```bash
python exploit.py -ip <IP_ADDRESS_FOR_LISTEN> -p <PORT_FOR_LISTEN> -u <USERNAME> -pwd <PASSWORD>
```
```bash
python ./exploit.py -ip 10.10.16.5 -p 1337 -u openplc -pwd openplc
```

### Arguments

- `-ip`  <IP_ADDRESS>: Specifies the IP address to listen on.
- `-p`   <PORT>: Specifies the port to listen on.
- `-u`   <USERNAME>: Specifies the username for OpenPLC login.
- `-pwd` <PASSWORD>: Specifies the password for OpenPLC login.

## Description

This script exploits the CVE-2021-31630 vulnerability in OpenPLC, allowing remote code execution on the WifineticTwo box. It establishes a connection to the target IP and port, authenticates with the provided username and password, and uploads a malicious payload to execute arbitrary code.

## Author

Created by [z1ntrx](@Hunt3r0x)

## Disclaimer

This script is intended for educational and testing purposes only. Use it responsibly and only on systems you have explicit permission to test.
