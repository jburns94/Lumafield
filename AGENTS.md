# Lumafield

## Cursor Cloud specific instructions

This repository is **documentation-only**. It contains a small set of Markdown
files (a `README.md` and several Lumafield sales "deal summary" /
business-justification documents). There is:

- **No source code** (no `.py`, `.js`, `.ts`, etc.).
- **No package manifest** (no `package.json`, `requirements.txt`, `pyproject.toml`, `go.mod`, etc.).
- **No services, build, lint, or automated test suite** to run.

### Working in this repo

- There is nothing to install, build, run, or test. The "update script" is
  intentionally a no-op health check.
- The core workflow is simply reading/editing the Markdown deal summaries.
- If you want a rendered preview of the Markdown (tables render much more
  readably than raw text), you can convert and serve it locally. Python 3 and
  Node are available in the environment, but no Markdown renderer is installed by
  default (and none should be added to the repo). Install one ad-hoc for a
  one-off preview only, e.g. `pip3 install --break-system-packages markdown`,
  render to a temp directory, and serve with `python3 -m http.server`.
- Do not add tooling/dependencies to the repo solely to enable previews unless
  the task explicitly asks for it.
