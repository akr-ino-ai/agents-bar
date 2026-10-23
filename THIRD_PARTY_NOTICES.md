# Third-Party Notices / 第三者ソフトウェアのライセンス表記

Agents Bar `0.1.0-beta.2` には、以下の第三者ソフトウェアおよびデータが含まれています。各ライセンスの条件に従い、著作権表示と許諾表示を掲載します。

This product includes the third-party software and data listed below. Their copyright and permission notices are reproduced as their licenses require.

| 名前 | 版 | ライセンス | 配布物での形 |
| :-- | :-- | :-- | :-- |
| Electron | 44.3.0 | MIT | アプリの実行基盤。同梱の `LICENSE.electron.txt` |
| Chromium、Node.js ほか Electron に含まれるコンポーネント | Electron 44.3.0 同梱版 | 各コンポーネントのライセンス（BSD-3-Clause、MIT ほか） | 同梱の `LICENSES.chromium.html` に全文 |
| React | 18.3.1 | MIT | 画面の描画（ビルド時に結合・圧縮） |
| React DOM | 18.3.1 | MIT | 同上 |
| scheduler | 0.23.2 | MIT | React DOM の依存（同上） |

次のものは**同梱していません**。利用者が別途導入するもので、それぞれの提供元の条件に従います。

- **Node.js** — フックの実行に使う外部のランタイム（22.12以上）
- **CodexBar** — 利用量表示に使う第三者製ソフトウェア。このアプリは導入済みの `codexbar-cli.exe` を呼び出すだけです
- **Claude Code / Claude Desktop、Codex / ChatGPT デスクトップアプリ** — 連携先のエージェント

---

## Electron

```
Copyright (c) Electron contributors
Copyright (c) 2013-2020 GitHub Inc.

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```

Electron に含まれる Chromium、Node.js、V8 などのライセンス全文は、アプリに同梱の `LICENSES.chromium.html` に収録されています。

## React, React DOM, scheduler

React 18.3.1、React DOM 18.3.1、scheduler 0.23.2 は同一のライセンス文です。

```
MIT License

Copyright (c) Facebook, Inc. and its affiliates.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## Feather Icons

設定画面のナビゲーションアイコン（`CategoryIcon.tsx`）の SVG パスは Feather Icons に由来します。

- 出典: https://feathericons.com/ （https://github.com/feathericons/feather）
- ライセンス: MIT License

```
The MIT License (MIT)

Copyright (c) 2013-2023 Cole Bemis

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 商標について

OpenAI、ChatGPT、Codex は OpenAI の商標です。Anthropic、Claude は Anthropic の商標です。このアプリは OpenAI および Anthropic とは無関係で、両社が承認・後援したものではありません。エージェントの名称は、どのエージェントの情報かを示す目的でのみ表示しています。両社のロゴは使用していません。
