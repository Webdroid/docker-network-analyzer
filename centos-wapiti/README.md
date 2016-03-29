# Usage
```
docker run -v $(pwd):/workdir webdroid/centos-wapiti <url> <option>
```

# Help
```
docker run -v $(pwd):/workdir webdroid/centos-wapiti -h
```

# Example
```
docker run -v $(pwd):/workdir webdroid/centos-wapiti www.mydomain.com --nice 5 --color --verbose 2 --scope folder --format html --verify-ssl 1
```

# Results 
Result will be stored in folder .wapiti inside your current working directory on your local machine
