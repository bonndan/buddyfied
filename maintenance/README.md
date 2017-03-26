# Buddy.works with Ansible

* define an environment variable named HOST which contains the address of the target system

```
docker run -e HOST=myhost.net -e SUDO_PASSWORD=test123 bonndan/buddyfied:maintenance
```

References:
http://stackoverflow.com/questions/18195142/safely-limiting-ansible-playbooks-to-a-single-machine
