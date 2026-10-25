# miformulas-support

MiFormulas アプリの紹介ページとプライバシーポリシー。`main` に push すると、GitHub Pages に公開される。

- `INDEX.md` / `INDEX_EN.md`: 紹介ページ（`/` と `/en/`）
- `PRIVACY_POLICY.md` / `PRIVACY_POLICY_EN.md`: プライバシーポリシー（`/privacy-policy/` と `/privacy-policy/en/`）

ポリシーを変えるときは、日英の両方で front matter の `version` と `lastUpdated`、「ポリシーのバージョン履歴」の先頭の行をそろえる。CI（`ci_scripts/check_privacy_policy_version.py`）が確かめる。仕組みは [midiccio-support](https://github.com/kazweda/midiccio-support) と同じ。
