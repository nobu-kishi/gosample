# hclwriteを使ったサンプルプログラム

## 1. 作業ディレクトリに移動

```bash
cd /gosample
```

## 2. Goモジュール初期化

```bash
go mod init main
```

## 3. 必要ライブラリを取得

```bash
go mod tidy
```

## 4. スクリプトの実行方法

### 方法1: `go run` を使う

```bash
go run main.go
```

### 方法2: `go build` してから実行する

```bash
go build -o main
./main
```

## 参考

https://pkg.go.dev/github.com/hashicorp/hcl/v2/hclwrite