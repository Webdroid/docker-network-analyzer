# Usage
```
docker run  webdroid/centos-nmap <nmap Option>
```

# Help 
```
docker run  webdroid/centos-nmap --help
```

# Example

## Scan TCP connect 
```
docker run  webdroid/centos-nmap -sT 127.0.0.1
```

## Scan SYN Stealth  
```
docker run  webdroid/centos-nmap -sS 127.0.0.1
```

## Scan FIN
```
docker run  webdroid/centos-nmap -sF 127.0.0.1
```

## Scan OS verbose
```
docker run  webdroid/centos-nmap -v -A 127.0.0.1
```
