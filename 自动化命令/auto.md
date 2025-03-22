## 工具01：

```shell
rad_windows_amd64.exe  --url-file urls.txt -http-proxy 127.0.0.1:9999 -wait-login

xray
xray_windows_amd64.exe webscan --listen 127.0.0.1:9999 --html-output dot.html

指纹识别:
hfinger.exe -l 127.0.0.1:9999 -p http://127.0.0.1:9999 --output-xlsx hfin.xlsx
```

