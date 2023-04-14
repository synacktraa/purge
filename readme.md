<p align="center">
<img src="https://imgur.com/w993TXD.png" alt="PURGE"/>
</p>

<h3 align="center">
A script that nobody asked for! Introducing an incredible tool for uncovering cache purge request vulnerability that don't even need pesky authentication. Enjoy the risk! 
</h3>

##  Usage

```bash
$ purge
```

```
|Usage:
|  purge subdomain.txt
|  cat subdomain.txt | purge
|  subfinder -d domain.TLD | purge
|
|if [ URL = PURGE'd ]; then [smash]
|else [pass] fi
```

```bash
$ cat subdomains.txt | purge
# OR
$ purge subdomains.txt
```

##  Installation

```bash
git clone https://github.com/synacktraa/purge.git && cd ./purge
sudo mv ./purge /usr/local/bin
cd .. && rm -rf "./purge"
```

##  Dependencies

- curl
- jq

