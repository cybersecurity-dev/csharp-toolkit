# [C#](https://dotnet.microsoft.com/en-us/languages/csharp) [Toolkit](https://dotnet.microsoft.com/en-us/learn/csharp)


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
