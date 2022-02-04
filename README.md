# integralsbot
積分botの解法を纏めます。
<a href="list.json"><code>list.json</code></a>に登録した積分が、
<a href="https://benri.ga/math/integralsbot/">こちら</a>から閲覧できます。

# list.jsonの書き方
```json
{
  "tw_uri":"元ツイートのURL",
  "solution_uri":"解法のURI",
  "TeX":"ツイート内容のTeX",
  "status":"ステータス",
  "keywords":[]
}
```
| ステータス | 値 |
| --------- | - |
| 解けていない | 0 |
| 解法を書いたhtmlがGitHub上にある | 1 |
| 解法へのリンクがある | 2 |
| 解法を書いたbmdファイルがGitHub上にある | 3 |

# bmdの書き方
エセMarkdownです。Mathlogに似ています。
```md
#見出し
##小見出し

&&&thm
定理
&&&

&&&prf
証明
&&&

&&&math
数式(KaTeX)
&&&
```
が使えます。

# file/
ファイルは<a href="file/"><code>file/</code></a>内に適当に置いてください。
ステータスが1または3に設定された積分の解法のURIには、<code>file/</code>からのパスを指定してください。
