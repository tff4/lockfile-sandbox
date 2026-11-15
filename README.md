# lockfile-sandbox

Synthetic dependency files for testing automated dependency-update pull requests. Not a real project: there is no
code, and nothing here is built or run. The pins are deliberately old.

- `requirements.txt` — a pip pin
- `python-app/` — a uv project and its `uv.lock`
- `web/` — an npm project and its `package-lock.json`
