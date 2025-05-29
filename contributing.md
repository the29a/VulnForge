# Contributing Guide
## Fork the Repository
Clone repository: 
```shell
git clone https://github.com/the29a/VulnForge
```

## Create a New Branch
### Feature branch
```shell
git checkout -b feat/your-feature-name
```
### Fix branch
```shell
git checkout -b fix/issue-description
```
If you get an error, you may need to fetch first, by using:
```shell
git remote update && git fetch
```
> [!NOTE]  
> Use one branch per fix / feature.

## Make Your Changes
- Test your changes or new CVEs
- Follow the existing code formatting and style
- Write/Update documentation
- Add comments for complex logic

## Commit Your Changes
- Write clear, descriptive commit messages
- Reference any related issues in your commit message
- Please make sure your commits follow the [conventions](https://gist.github.com/robertpainsi/b632364184e70900af4ab688decf6f53#file-commit-message-guidelines-md)
- Commit to the forked repository
  - Example: `git commit -am "Feat: Add CVE-2023-XXXXX"`


## Push and Create Pull Request
- Push to your fork: `git push origin feat/cve-2025-00000`
- Create a Pull Request
- Make sure you send the PR to the `feat/cve-2025-00000` branch

