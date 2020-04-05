Created using [**Academic**](https://github.com/gcushen/hugo-academic).

## Install latest Hugo on Ubuntu/Debian
_From https://jameskiefer.com/posts/install-latest-hugo-on-ubuntu-debian/_

```
wget $(curl -s https://api.github.com/repos/gohugoio/hugo/releases/latest | grep -oP '"browser_download_url": "\K(.*)hugo_extended(.*)Linux-64bit.deb')
sudo dpkg -i hugo_extended*Linux-64bit.deb
```

