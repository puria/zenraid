# [Zenraid](https://pn-a.com/zenraid)
Debug zenroom output online

For when you are too lazy to type

```bash
zenroom -z -c "logfmt=json" broken.zen 2>&1 >/dev/null | grep "J64"| cut -d" " -f3|cut -d"\"" -f1|base64 -d|jq
```


https://github.com/puria/zenraid/assets/10379/41fcffb6-17f2-473b-8ea4-d8f2b7b1166c

