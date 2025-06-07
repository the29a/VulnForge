# VulnForge
<p align="center">
    <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/the29a/vulnforge">
    <img alt="GitHub contributors" src="https://img.shields.io/github/contributors-anon/the29a/VulnForge">
    <a href="https://github.com/the29a/VulnForge/blob/main/LICENSE" target="_blank"><img alt="GitHub License" src="https://img.shields.io/github/license/the29a/VulnForge">
</p>

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