# IDOR

### Description

when a modified URL returns private data to an unauthorized user, this is
classified as an `IDOR`

### Impacts

exposes sensitive data for unauthorized users

### "Types"

- `URL`: query vuln
- `cookie`: query vuln
- `hidden input`: command vuln

### Others Techniques

- **http post pollution**

send multiple parameters to obfuscate the attack parameter

### Tools

- mitmproxy

