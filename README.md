# HADA Base Template — Sample

This repository is a small, fictional demonstration of the HADA Base operating
foundation. The example under `examples/` illustrates a project profile and one dated
decision record. All sample names and details are invented.

Start with [`AGENTS.md`](AGENTS.md), then inspect the example. Root [`WHY.md`](WHY.md)
is intentionally only a purpose placeholder; it contains no real person's reasoning.
Conversation logging is disabled by default. To try manual imports in a copied project,
copy `config/project.example.json` to `config/project.json`, set
`features.conversation_logging` to `true`, and run
`python tools/import_conversation.py --source PATH_TO_EXPORT`.
