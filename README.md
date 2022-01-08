<h1 align="center"><i>MK</i></h1>
<p align="center"><i>SuperB</i> way to create new folders and files</p>
<p align="center"><a href="https://github.com/NNBnh/mk/blob/main/LICENSE"><img src="https://img.shields.io/github/license/NNBnh/mk?labelColor=073551&color=4EAA25&style=for-the-badge" alt="License: GPL-3.0"></a> <a href="https://gist.github.com/NNBnh/9ef453aba3efce26046e0d3119dab5a7#development-completed"><img src="https://img.shields.io/badge/development-completed-%234EAA25.svg?labelColor=073551&style=for-the-badge&logoColor=FFFFFF" alt="Development completed"></a></p>

## 💡 About
**SuperB MK** (a.k.a `mk`) is a *SuperB* files and folders creation tool written in [`portable sh`](https://github.com/dylanaraps/pure-sh-bible) inspired by [**Advanced New File**](https://github.com/tanrax/terminal-AdvancedNewFile).

## 🚀 Setup
### 🧾 Dependencies
- [Unix commands](https://en.wikipedia.org/wiki/List_of_Unix_commands) to process

### 📥 Installation
#### 🔧 Manually
Option 1: using `curl`
```sh
curl https://raw.githubusercontent.com/NNBnh/mk/main/bin/mk > ~/.local/bin/mk
chmod +x ~/.local/bin/mk
```

Option 2: using `git`
```sh
git clone https://github.com/NNBnh/mk.git ~/.local/share/mk
ln -s ~/.local/share/mk/bin/mk ~/.local/bin/mk
```

#### 📦 Package manager
For [Arch-Linux base distro](https://archlinux.org), install [this AUR package](https://aur.archlinux.org/packages/superbmk-git):
```sh
paru -Sy superbfetch-git
```

For [Bpkg](https://github.com/bpkg/bpkg) user:
```sh
bpkg install NNBnh/mk
```

For [Basher](https://github.com/basherpm/basher) user:
```sh
basher install NNBnh/mk
```

> *If you can and want to port SuperB MK to other package managers, feel free to do so.*

## ⌨️ Usage
Run 'mk' in the terminal:
```sh
mk ITEMS
```

Examples:
```sh
mk file.txt folder/ {foo,bar}/{'hello world'/{1,2,3},test}
```

Result:
```console
~/
├─ file.txt
│
├─ folder/
│
├─ foo/
│ ├─ hello world/
│ │ ├─ 1
│ │ ├─ 2
│ │ └─ 3
│ │
│ └─ test
│
└─ bar/
  ├─ hello world/
  │ ├─ 1
  │ ├─ 2
  │ └─ 3
  │
  └─ test
```

## 💌 Credits
Special thanks to:
- [**Julian Marcos**](https://github.com/Juliaria08) for porting this package to the [AUR](https://aur.archlinux.org/packages/superbfetch-git)
- [**Advanced New File**](https://github.com/tanrax/terminal-AdvancedNewFile) by [Andros Fenollosa](https://github.com/tanrax)

<br><br><br><br>

---

> <h1 align="center">Made with ❤️ by <a href="https://github.com/NNBnh"><i>NNB</i></a></h1>
>
> <p align="center"><a href="https://www.buymeacoffee.com/nnbnh"><img src="https://img.shields.io/badge/buy_me_a_coffee%20-%23F7CA88.svg?logo=buy-me-a-coffee&logoColor=333333&style=for-the-badge" alt="Buy Me a Coffee"></a></p>
