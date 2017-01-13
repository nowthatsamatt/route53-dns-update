When your home IP changes run this with a new IP:

```source ~/.cloud_credentials/nowthatsamatt```

```aws route53 change-resource-record-sets --hosted-zone-id ZLKX5JGAFVCJE --change-batch file:///Users/matt.cupples/github/route53-dns-update/home.nowthatsamatt.com.json```
