## PATCHED

# Tiktok Share Bot
Creds to [MonkeySkid](https://github.com/monkeyskid)

### Only use 100-1000 threads recommended, you might run into problems if you go any higher

## Installation Linux

Change to a temporary directory for the installation.

1 Go to tmp

```cd /tmp```
Select the latest package for your architecture from https://golang.org/dl/ and download it.

```wget https://golang.org/dl/go1.<VERSION_NUMBER>.linux-amd64.tar.gz```

2 Extract to the Installation Location
Extract the Golang executable to /usr/local.

```sudo tar -C /usr/local -xzf go1.<VERSION_NUMBER>.linux-amd64.tar.gz```

3 Set Environment
To use Golang, set the required environment variables in your .profile.

```echo "export PATH=$PATH:/usr/local/go/bin" >> ~/.profile```

```echo "export GOPATH=~/.go" >> ~/.profile```

Reload your profile to begin using Golang.

```source ~/.profile```

4 Test the Installation
Verify you installed the expected version of Golang.

```go version```

# go version go1.<VERSION_NUMBER> linux/amd64


## Installation


### Ubuntu
```bash
sudo apt update
sudo apt install golang-go
git clone https://github.com/SoftyMods/TiktokShares.git
cd Tiktok-Sharebot
go run .
```


### Windows
Go to the [Go download page](https://go.dev/dl/)
```bash
git clone https://github.com/SoftyMods/TiktokShares.git
go run .
```
You can also build it to an exe.
```bash
go build
```

### Mac
Go fuck yourself
