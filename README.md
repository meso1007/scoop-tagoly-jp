# Scoop Bucket for Tagoly-JP

このリポジトリは Tagoly-JP を Windows で Scoop 経由でインストールするためのバケットです。

## インストール方法

1. Scoop にこのバケットを追加

```powershell
scoop bucket add tagoly-jp https://github.com/meso1007/homebrew-tagoly-jp-scoop
```

2. Tagoly-JP をインストール
```powershell
scoop install tagoly-jp/tagoly-jp
```

## 確認
```powershell
tagoly-jp --version
tagoly-jp
```

---

ポイント：

- GitHub リリースのバイナリを `url` に指定  
- SHA256 を `hash` に記載することで安全にダウンロード可能  
- `bin` で PATH に追加されるファイルを指定  

