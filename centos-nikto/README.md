# Usage
```
docker run  webdroid/centos-nikto <nikto Option>
```

# Help
```
docker run  webdroid/centos-nikto -h
```

# Example

## Scan Port 80
```
docker run  webdroid/centos-nikto -host 127.0.0.1
```

## Scan SSL on Port 443
```
docker run  webdroid/centos-nikto -host 127.0.0.1 -p 443 -ssl
```

## Scan Port 80 and 443
```
docker run  webdroid/centos-nikto -host 127.0.0.1 -p 80,443
```
