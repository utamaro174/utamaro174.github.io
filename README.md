# utamaro174.github.io

アプリの公開ページ（GitHub Pages）。

- `kanji/privacy.html` / `kanji/privacy-en.html` … 「先取り 漢字マスター」のプライバシーポリシー。
  原本は F131_Kanji の `lib/ui/privacy_policy_text.dart`。`tool/privacy_to_html.py` で `site/` に書き出し、ここへコピーする。
- `anzan/privacy.html` / `anzan/privacy-en.html` … 「先取り 暗算マスター」のプライバシーポリシー。
  原本は F161_Anzan の `docs/privacy_policy.md` / `docs/privacy_policy_en.md`。
  `python tool/privacy_policy_html.py --site C:/Projects/utamaro174.github.io/anzan` で書き出す（直接編集しない）。
- `app-ads.txt` … AdMob の app-ads.txt（ストアの「開発者のウェブサイト」に https://utamaro174.github.io/ を登録する）。
