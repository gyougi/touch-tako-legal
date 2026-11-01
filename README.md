# touch-tako-legal

Public legal & support pages for the **Touch Tako** macOS app, served via GitHub Pages.

- `privacy.html` — Privacy Policy (JA / EN / 简体中文)
- `support.html` — Support & FAQ (JA / EN / 简体中文)
- `terms.html` — Terms of Use / subscription EULA (JA / EN / 简体中文)
- `index.html` — Landing

Live URLs (after Pages is enabled):

- https://gyougi.github.io/touch-tako-legal/
- https://gyougi.github.io/touch-tako-legal/privacy.html
- https://gyougi.github.io/touch-tako-legal/support.html
- https://gyougi.github.io/touch-tako-legal/terms.html

Contact: contact@glspace.co.jp

## 連絡先はどこに書いてあるか

この站には生成スクリプトが無いので、住所は**頁の中に素で**在る。
`contact@glspace.co.jp` を変えるときは、次の全部を直すこと ──
一つ直し忘れても頁は普通に出るので、**字面でも検査でも分からない**。

- `index.html`（2 件）
- `privacy.html`（6 件）
- `support.html`（6 件）
- `terms.html`（6 件）
- `README.md`（上の Contact の行）

見落としを確かめる一行:

```bash
grep -rn 'glspace\.co\.jp' . --include='*.html' --include='*.md' | grep -v contact@
```
