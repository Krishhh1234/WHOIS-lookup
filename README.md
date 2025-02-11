# WHOIS Lookup Script 🌐

## Description
This Python script allows you to perform a **WHOIS lookup** for any domain. It connects to the `whois.iana.org` server to fetch and display registration information, including domain ownership and other details.

## Features
- Connects to a WHOIS server using a TCP socket.
- Retrieves and displays raw WHOIS information for a given domain.
- Simple and lightweight implementation with no external dependencies.

## Example Usage
```python
print(whois_lookup("google.com"))



## Expected Output:
% IANA WHOIS server
% for more information on IANA, visit http://www.iana.org
...
