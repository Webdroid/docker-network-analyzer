# Usage
```
docker run  webdroid/rocky-nmap <nmap Option>
```

# Help 
```
docker run  webdroid/rocky-nmap --help
```

# Example

## Scan TCP connect 
```
docker run  webdroid/rocky-nmap -sT 127.0.0.1
```

## Scan SYN Stealth  
```
docker run  webdroid/rocky-nmap -sS 127.0.0.1
```

## Scan FIN
```
docker run  webdroid/rocky-nmap -sF 127.0.0.1
```

## Scan OS verbose
```
docker run  webdroid/rocky-nmap -v -A 127.0.0.1
```
