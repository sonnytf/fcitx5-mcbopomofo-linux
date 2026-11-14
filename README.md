# fcitx5-mcbopomofo-deb

透過 GitHub Actions 自動追蹤 [openvanilla/fcitx5-mcbopomofo](https://github.com/openvanilla/fcitx5-mcbopomofo) 最新 Release，於潔淨的 Ubuntu 容器環境編譯並使用 `dpkg-deb` + `dpkg-shlibdeps` 打包為 `.deb` 套件，發布至 GitHub Releases。

## 支援系統版本

- Ubuntu 22.04 LTS (`jammy`)
- Ubuntu 24.04 LTS (`noble`)
- Ubuntu 26.04 LTS (`resolute`)

## 安裝方式

至 [Releases](../../releases) 下載對應 Ubuntu 版本的 `.deb` 後執行：

```bash
sudo apt install ./fcitx5-mcbopomofo_*-1~ubuntu*_amd64.deb
```
