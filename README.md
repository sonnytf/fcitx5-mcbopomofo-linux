# fcitx5-mcbopomofo-linux

透過 GitHub Actions 自動追蹤 [openvanilla/fcitx5-mcbopomofo](https://github.com/openvanilla/fcitx5-mcbopomofo) 最新 Release，於各發行版潔淨容器環境編譯並打包為 `.deb` / `.rpm`，發布至 GitHub Releases。

## 支援發行版

### `.deb`（`dpkg-deb` + `dpkg-shlibdeps`）
- **Ubuntu**：22.04 (`jammy`)、24.04 (`noble`)、26.04 (`resolute`)
- **Linux Mint**：21 / 22（分別相容 Ubuntu 22.04 / 24.04 `.deb`）
- **Debian**：12 (`bookworm`)、13 (`trixie`)

### `.rpm`（`rpmbuild`）
- **Fedora**：43、44

## 安裝方式

至 [Releases](../../releases) 下載對應發行版套件後執行：

```bash
# Ubuntu / Debian / Linux Mint
sudo apt install ./fcitx5-mcbopomofo_*_amd64.deb

# Fedora
sudo dnf install ./fcitx5-mcbopomofo-*.x86_64.rpm
```
