<p align="center"><a href="https://github.com/cybersecurity-dev/awesome-csharp-programming-language">
  <img width="10%" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/CSharp.svg" />
</a></p>

# [C#](https://dotnet.microsoft.com/en-us/languages/csharp) [Development](https://dotnet.microsoft.com/en-us/learn/csharp) [Toolkit](https://github.com/cybersecurity-dev/awesome-csharp-programming-language)
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://github.com/cybersecurity-dev/Bash-Toolkit?tab=readme-ov-file#programming-language) [![Windows](https://custom-icon-badges.demolab.com/badge/Windows-0078D6?style=for-the-badge&logo=windows11&logoColor=white)](https://github.com/cybersecurity-dev/PowerShell-Toolkit?tab=readme-ov-file#programming-language)

## Install Steps

<details>

<summary>For Debian, Ubuntu, Linux Mint</summary>

```bash
wget https://packages.microsoft.com/config/debian/12/packages-microsoft-prod.deb -O packages-microsoft-prod.deb && \
sudo dpkg -i packages-microsoft-prod.deb
```

```bash
rm packages-microsoft-prod.deb && \
sudo apt-get update && \
sudo apt-get install -y dotnet-sdk-9.0 
```

```bash
sudo dotnet workload update && \
dotnet --version
```

</details>


<details>
 
 <summary>For RHEL, Fedora, AlmaLinux</summary>
  
 ```bash
 sudo dnf update
 ```
 </details>

 <details>
 <summary>For Arch, Manjaro, EndeavourOS</summary>
  
 ```bash
sudo pacman -Syu
 ```
 </details>


## HelloWorld Project
```bash
dotnet new console -lang C# -o HelloWorld && \
cd ./HelloWorld && \
dotnet run
```




##

### Contributing

[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors

[Thanks goes to these contributors](https://github.com/cybersecurity-dev/Csharp-Toolkit/graphs/contributors)!

[🔼 Back to top](#c-development-toolkit)
