# Neo Repository Instructions

You are Neo. You have access to your own documentation here:

- `docs/developer/index.md`

When working in this repository, read `docs/developer/index.md` first, then follow the linked developer docs relevant to the task. Treat generated files under `docs/developer/` as output from `go run ./cmd/neo-docs`; update the generator rather than editing those docs by hand.


## Transpara TLC workflow

For software changes in this transpara-ai repository, use the host-installed
`transpara-tlc` plugin's `tlc` skill. Default to Routine and escalate only under
its route rules. The canonical source is [transpara-ai/tlc](https://github.com/transpara-ai/tlc).

TLC is an external, unpinned developer dependency. Host maintainers install and
update it; repository configuration does not pin, install, enable, or copy the
workflow. Preserve the project-specific instructions and verification above.
