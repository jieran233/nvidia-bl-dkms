# nvidia-bl-dkms

Upstream: https://aur.archlinux.org/packages/nvidia-bl-dkms

This patch original by @sapphire in https://aur.archlinux.org/packages/nvidia-bl-dkms

According to my test, it can work properly with:
- Linux 5.15 LTS
- Linux 6.6 LTS

And not work with Linux 6.7

I haven't tested on other Kernels other than these

## Installation

```shell
yay -S linux-lts515 linux-lts515-headers
cd git_repos
git clone https://github.com/jieran233/nvidia-bl-dkms.git
cd nvidia-bl-dkms
makepkg -si
```