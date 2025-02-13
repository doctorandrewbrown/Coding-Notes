- Identify processes on port e.g for port 8080
```bash
  sudo lsof -i :8080
```
- above gives PID, then use below where 12345 is example PID for port 8080
```bash
  sudo kill -9 12345
```
- confirm kill when below repeated cmd gives no output
```bash
  sudo lsof -i :8080
```
