#### 屏蔽广告
阻止网站广告和软件广告，阻止网络跟踪，阻止恶意软件！

#### 科学上网
[Google]、[DuckDuckGo]、[Gmail]、[YouTube]、[Facebook]、[Twitter]、[Tumblr]、[Dropbox]、[OneDrive]、[Flickr]！

#### 项目地址
**项目地址**：`https://github.com/heiniao/hosts`  
**下载地址**：`https://raw.githubusercontent.com/heiniao/hosts/master/hosts`

#### 使用方法
```bash
# Linux
# Terminal

sudo mv /etc/hosts{,.backup}

sudo wget https://raw.githubusercontent.com/heiniao/hosts/master/hosts -O /etc/hosts

# Windows
# Windows PowerShell (Admin)

mv C:\Windows\System32\drivers\etc\hosts C:\Windows\System32\drivers\etc\hosts.backup

wget https://raw.githubusercontent.com/heiniao/hosts/master/hosts -O C:\Windows\System32\drivers\etc\hosts

# Asuswrt-Merli

rm -rf /tmp/hosts
wget --no-check-certificate https://raw.githubusercontent.com/heiniao/hosts/master/hosts -O /tmp/hosts
rm -rf /jffs/configs/hosts
mv /tmp/hosts /jffs/configs/hosts
```

[Google]: https://www.google.com/ncr
[DuckDuckGo]: https://duckduckgo.com/
[Gmail]: https://mail.google.com/
[YouTube]: https://www.youtube.com/
[Facebook]: https://www.facebook.com/
[Twitter]: https://twitter.com/
[Tumblr]: https://www.tumblr.com/
[Dropbox]: https://www.dropbox.com/
[OneDrive]: https://onedrive.live.com/
[Flickr]: https://www.flickr.com/
