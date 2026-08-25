# context-mode is active

Use Pi's native `read` / `edit` / `grep` / `find` / `ls` / `bash` tools for
exact files, instructions, edits, and small bounded checks. Prefer
`ctx_batch_execute` or `ctx_execute` for repository-wide exploration, repeated
searches, multi-file analysis, and commands expected to produce substantial
output. Use `ctx_execute_file` when sandboxed processing of a known file is
useful.
