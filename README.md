# electron でアプリケーションを作る

## npx upgrage

```sh
yarn create react-app react-beginner
```

<https://github.com/ymd65536/react-beginner-typescript>

```sh
yarn create react-app react-beginner-typescript --template typescript
```

<https://github.com/ymd65536/react-beginner>

## Setup

## commands

```text
Inside that directory, you can run several commands:

  yarn start
    Starts the development server.

  yarn build
    Bundles the app into static files for production.

  yarn test
    Starts the test runner.

  yarn eject
    Removes this tool and copies build dependencies, configuration files
    and scripts into the app directory. If you do this, you can’t go back!

We suggest that you begin by typing:

cd hello
yarn start
```

## トラブルシューティング

```text
App threw an error during load
/Users/{アカウントID}/Desktop/react-beginner/src/App.js:1
import logo from './logo.svg';
^^^^^^

SyntaxError: Cannot use import statement outside a module
```

React プロジェクトにElectron を導入しようとするとimportでエラーになる。
書き換えが必要。

ちなみにReactプロジェクトを保ったまま、Electron のプロジェクトも作成できる。
