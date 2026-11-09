# folio-models

Translation models for [Folio](https://euhaan.github.io/folio/), a document viewer that translates on the device.

Folio downloads a language only when its user asks for it in 설정 · 도움말 → 번역 언어, keeps it on the device, and lets the user delete it. Documents are never sent anywhere: only these files are downloaded.

| Folder | Direction |
|---|---|
| `v1/ko-en`, `v1/en-ko` | Korean ⇄ English |
| `v1/ja-en`, `v1/en-ja` | Japanese ⇄ English |
| `v1/zh-en`, `v1/en-zh` | Chinese (Simplified) ⇄ English |

The models are Mozilla's Firefox Translations models ("base-memory" releases from Mozilla's model registry), unchanged, under the Mozilla Public License 2.0 (see `LICENSE`). They run in [bergamot-translator](https://github.com/browsermt/bergamot-translator) (MPL-2.0). Source of the models: https://github.com/mozilla/translations
