# A5.8.17 media question support

This folder contains bundled question-bank assets for V27.0-A5.8.17.

Runtime bundled import:
- all_bundled_questions_a5817.json / qbank_bundle_a5817.js: 765 questions.
- Batch 1: 426 questions.
- Batch 2 safe no-image: 339 questions.

Media candidates:
- 37 rows from batch 2 were flagged as possibly requiring maps, charts, diagrams, tables, or figures.
- These are intentionally kept in manual_review/ until source images are prepared and linked with media_src.

Supported media columns in CSV / JSON:
- media_type: image
- media_src: assets/qbank_bundled/a5817/media/example.png
- media_alt
- media_caption
- media_position: after_question
- allow_zoom: true / false
