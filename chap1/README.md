# Introductionのメモ

## 環境構築

### インストール

```sh
$ curl https://sh.rustup.rs -sSf | sh
```

1を選択

### Pathを通す

 ~/.zshrc
```diff
+ export PATH="$HOME/.cargo/bin:$PATH"
```

```sh
$ source ~/.zshrc
$ rustc --version
rustc 1.23.0 (766bd11c8 2018-01-01)
```

OK

