# Windows requirements

winget install --accept-source-agreements chocolatey.chocolatey
choco install -y neovim git ripgrep wget fd unzip gzip mingw make

# Add Nerd Font from https://www.nerdfonts.com/font-downloads

Ubuntu Mono for example, select all *.ttf files and right-click install

# Install PowerShell "Core" with pwsh.exe available and add it to PATH env. var.

https://aka.ms/powershell-release?tag=stable

git clone https://github.com/Shiaroku/kickstart.nvim.git $env:USERPROFILE\AppData\Local\nvim\