# minimal react typescript storybook

最小構成の React+TypeScript の Storybook のプロジェクト。

アプリケーションはビルドできない。

## セットアップ

以下のコマンドで Storybook のプロジェクトを作成する。

```shell
$ npx sb init
```

このコマンドはプロジェクトの種類（React、Vue など）を判定し、それに基づいた Storybook のプロジェクトを作成する。

そのため、空のディレクトリでこのコマンドを実行しても失敗する。

事前に React や Vue をインストールしておく必要がある。

### React+TypeScript をサポートする Storybook のプロジェクトを作成するためには

以下のコマンドで、React と TypeScript をインストールしておけば良い。

```shell
$ npm i react react-dom -S
```

```shell
$ npm i @types/react @types/react-dom typescript -D
```

上記を実行後、`npx sb init`を実行すれば React+TypeScript をサポートする Storybook のプロジェクトが作成される。
