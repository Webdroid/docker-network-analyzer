# Usage
Run GUI:
```
docker run -p 9292:9292 webdroid/centos-arachni
```

Run Command line:
```
docker run -v $(pwd):/workdir --entrypoint=arachni webdroid/centos-arachni <Parameter>
```

# Help
```
docker run -v $(pwd):/workdir --entrypoint=arachni webdroid/centos-arachni -h
```

# Example
```
docker run -v $(pwd):/workdir --entrypoint=arachni webdroid/centos-arachni http://192.168.0.1/
```

# Information
Administrator user
E-mail: admin@admin.admin
Password: administrator

Regular user 
E-mail: user@user.user
Password: regular_user

