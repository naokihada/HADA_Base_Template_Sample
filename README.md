# HADA Base Template — Sample

This repository is a small, fictional demonstration of the HADA Base operating
foundation. The example under `examples/` illustrates a project profile and one dated
decision record. All sample names and details are invented.

Start with [`AGENTS.md`](AGENTS.md), then inspect the example. Root [`WHY.md`](WHY.md)
is intentionally only a purpose placeholder; it contains no real person's reasoning.
When a project owner states a durable reason or adopts a proposed reason, record it in
the applicable WHY file with `python tools/record_why.py --root PROJECT_ROOT`. The
command prompts for the reason and appends a dated entry without replacing earlier
entries. If WHY.md is missing, nonblank input creates a purpose-only header before the
entry. Blank input does not create or change the file. The Sample test suite simulates
this input against a temporary copy of the Sample WHY file. For a multi-line reason,
enter a single period on its own line to finish; blank lines inside the entry are kept.
Conversation logging is disabled by default. To try manual imports in a copied project,
copy `config/project.example.json` to `config/project.json`, set
`features.conversation_logging` to `true`, and run
`python tools/import_conversation.py --source PATH_TO_EXPORT`.
