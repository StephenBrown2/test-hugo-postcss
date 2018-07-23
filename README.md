# Test Hugo site

### Steps to reproduce

1. Checkout this repo
2. Run `npm install`
3. Run `./hugo -v server | grep -v WARN`
4. Notice messages:
```
INFO 2018/07/23 15:30:48 Using config file: /home/stephen/git/hub/test-hugo/config.toml
Building sites … INFO 2018/07/23 15:30:48 syncing static files to /
INFO 2018/07/23 15:30:48 found taxonomies: map[string]string{"tag":"tags", "category":"categories"}
INFO 2018/07/23 15:30:48 postcss: use config file /home/stephen/git/hub/test-hugo/postcss.config.js
Input Error: Did not receive any STDIN
ERROR 2018/07/23 15:30:49 error: failed to transform resource: exit status 1
Total in 1138 ms
Error: Error building site: logged 1 error(s)
```
