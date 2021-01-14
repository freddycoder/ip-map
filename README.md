# ip-map
The most simple ip map page that i can imagine

## Extract ip from logs

To get the ips adresses from my log I use the command

```
cat my_logs.txt | grep -oE "\b([0-9]{1,3}\.){3}[0-9]{1,3}\b" | sort | uniq
```

After I paste the result in the textarea of the page and press 'show ips location'. 
