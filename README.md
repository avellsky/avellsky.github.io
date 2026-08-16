# avellsky.github.io

GitHub Pages で公開しているサイトの中身です。ここに置いたものが、そのまま
<https://avellsky.github.io/> 以下で配信されます。

## 置いてあるもの

| 場所 | 公開先 | 内容 |
|---|---|---|
| `Meteorium/` | [/Meteorium/](https://avellsky.github.io/Meteorium/) | Meteorium のサポートページ一式 |
| `Cometarium/` | [/Cometarium/](https://avellsky.github.io/Cometarium/) | Cometarium のサポートページ一式 |

内訳は下のとおりです。

## Astrarium はここではない

[/Astrarium/](https://avellsky.github.io/Astrarium/) は、**別のリポジトリ**
[avellsky/Astrarium](https://github.com/avellsky/Astrarium) の `gh-pages` 枝が
出しています。GitHub Pages は、同じ名前のリポジトリのプロジェクトページを
利用者サイトの同名フォルダより先に取るためです。

以前はここにも `Astrarium/` を置いていましたが、**影になっていて一度も公開されて
いませんでした**（2026-08-14 に入れた表紙のロゴが site に出ないので気づいた）。
二重に持つと必ず片方が古くなるので、2026-08-16 に消しました。

Astrarium のサポートページ・プライバシーポリシー・マニュアルを更新するときは、

    cd astrarium/apps/Astrarium
    git fetch git@github.com:avellsky/Astrarium.git gh-pages:refs/remotes/gh/gh-pages
    git worktree add --detach <一時ディレクトリ> gh/gh-pages
    # index.html / icon*.png / manual/*.pdf を入れ替えて commit
    git push git@github.com:avellsky/Astrarium.git HEAD:gh-pages

の順です（`origin` は HTTPS で認証が通らないので、SSH の URL を直に指定します）。
App Store の「サポート URL」「プライバシーポリシー URL」もこの枝が答えています。

## ここに無いもの

アプリのソースコードは非公開です。このリポジトリは公開用のページと配布物を置く
場所で、計算コアや UI の実装は含みません。

---

Astrarium © 2026 Avellsky. All rights reserved.

## Meteorium

| 場所 | 公開先 | 内容 |
|---|---|---|
| `Meteorium/index.html` | [/Meteorium/](https://avellsky.github.io/Meteorium/) | Meteorium のサポートページ。マニュアル、プライバシーポリシー、連絡先 |
| `Meteorium/manual/` | [/Meteorium/manual/](https://avellsky.github.io/Meteorium/manual/) | ユーザーマニュアル（日本語・英語、HTML / Markdown） |
| `Meteorium/privacy-policy.ja.html` | [/Meteorium/privacy-policy.ja.html](https://avellsky.github.io/Meteorium/privacy-policy.ja.html) | プライバシーポリシー（日本語） |
| `Meteorium/privacy-policy.en.html` | [/Meteorium/privacy-policy.en.html](https://avellsky.github.io/Meteorium/privacy-policy.en.html) | プライバシーポリシー（英語） |
| `Meteorium/icon.png` | — | アプリのアイコン |

## Cometarium

| 場所 | 公開先 | 内容 |
|---|---|---|
| `Cometarium/index.html` | [/Cometarium/](https://avellsky.github.io/Cometarium/) | Cometarium のサポートページ。マニュアル、プライバシーポリシー、連絡先 |
| `Cometarium/manual/` | [/Cometarium/manual/](https://avellsky.github.io/Cometarium/manual/) | ユーザーマニュアル（日本語・英語、HTML / Markdown、図入り） |
| `Cometarium/privacy-policy.ja.html` | [/Cometarium/privacy-policy.ja.html](https://avellsky.github.io/Cometarium/privacy-policy.ja.html) | プライバシーポリシー（日本語） |
| `Cometarium/privacy-policy.en.html` | [/Cometarium/privacy-policy.en.html](https://avellsky.github.io/Cometarium/privacy-policy.en.html) | プライバシーポリシー（英語） |
| `Cometarium/icon.png` | — | アプリのアイコン（無料版） |

マニュアルの図はアプリの実画面です。番号入りの解説図は元のスクリーンショットに
丸数字を重ねて作っており、画面を作り直したときは図も撮り直します。
