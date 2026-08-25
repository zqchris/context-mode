# context-mode is active

The Pi extension registers `ctx_*` tools before the agent turn and redirects
unbounded native inspection calls (`read`, `grep`, `find`, `ls`, and large
read-only `bash` output) to those tools. Small, explicitly bounded native
operations remain available. If the context-mode bridge is unavailable, the
extension allows native tools through so the session is not stranded.
