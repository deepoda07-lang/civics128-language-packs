# Civics 128 — Language Packs

Data files for the [Civics 128](https://github.com/deepoda07-lang) app's on-demand translation feature. The app bundles Turkish by default; when a user picks a different language, it downloads the matching pack from here (via [jsDelivr](https://www.jsdelivr.com/)) and caches it on-device.

Each `<lang>.json` file maps every glossary lemma (root word) from the app's 128 official civics questions to a translation and, where relevant, a short exam-context note in that language.

```json
{
  "govern": { "translation": "...", "civicsNote": "..." }
}
```

Served at: `https://cdn.jsdelivr.net/gh/deepoda07-lang/civics128-language-packs@main/<lang>.json`
