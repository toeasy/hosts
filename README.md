#### 屏蔽广告
This hosts file is a merged collection of hosts from reputable sources, with a dash of crowd sourcing via Github.

#### 科学上网
[Google]、[DuckDuckGo]、[Gmail]、[YouTube]、[Facebook]、[Twitter]、[Tumblr]、[Dropbox]、[OneDrive]、[Flickr]！

#### 文件下载
[hosts]

#### 使用方法
```sh
# Linux
sudo mv /etc/hosts{,.backup}
sudo wget --no-check-certificate https://raw.githubusercontent.com/heiniao/hosts/master/hosts -O /etc/hosts

# Windows
# Press Win + X keyboard shortcut to bring up Win + X menu. Then from the menu click Windows PowerShell (Admin).
# Windows PowerShell (Admin)
mv C:\Windows\System32\drivers\etc\hosts C:\Windows\System32\drivers\etc\hosts.backup
wget https://gitlab.com/hosts/hosts/raw/master/hosts -O C:\Windows\System32\drivers\etc\hosts
ipconfig /flushdns
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

[hosts]: https://raw.githubusercontent.com/heiniao/hosts/master/hosts
