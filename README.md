# VulnForge

Deploy, Detect, Exploit, Repeat.

VulnForge is an open-source collection of pre-build vulnerable Docker environments. VulnForge are made for testing vulnerable images detection and possible vulnerability exploitation.


## Usage
### Clone repository
```shell
git clone https://github.com/the29a/VulnForge.git
cd VulnForge
```

### Download project
```shell
# Download project
wget https://github.com/the29a/VulnForge/archive/refs/heads/main.zip -O vulnforge-main.zip
unzip vulnforge-main.zip
cd vulnforge-main

# Enter the directory of vulnerability/environment

# Build environment
docker compose build

# Run environment
docker compose up -d
```

After the test, stop the environment:
```shell
docker compose down -v
```