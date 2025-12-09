# uapf-quickstarts

**Quickstart recipes** for working with UAPF:

- Minimal “hello UAPF” projects for **Python** and **Node.js/TypeScript**.
- Copy-paste templates for new services that consume or expose `.uapf` packages.

This repo is intentionally small and opinionated – it’s meant to be cloned and adapted.

---

## Planned structure

```text
uapf-quickstarts/
  python-basic/
    README.md
    main.py
    example.uapf
    pyproject.toml / requirements.txt

  node-basic/
    README.md
    index.ts
    example.uapf
    package.json

  engine-service/
    README.md
    ...
```

Each subfolder is a fully self-contained project.

---

## Example: Python basic quickstart

In `python-basic/` you can:

- Load a `.uapf` file using [`uapf-python`](https://github.com/UAPFormat/uapf-python).
- Validate it.
- Traverse manifest, agents, and integration sections.
- Use this as a template for batch validation scripts or simple orchestrators.

---

## Example: Node basic quickstart

In `node-basic/` you can:

- Load a `.uapf` file using [`uapf-typescript`](https://github.com/UAPFormat/uapf-typescript).
- Run validation and log errors.
- Expose a simple HTTP endpoint that returns manifest data.

---

## How to use this repo

- Pick the language closest to your stack.
- Copy the relevant quickstart folder into your own project.
- Replace the example `.uapf` package with your own.

---

## Contributing

Please:

- Add new quickstarts as **subfolders**, not as top-level files.
- Keep each quickstart minimal and heavily commented.
- Use consistent naming and file layout so users can orient quickly.

---

## License

MIT – see org-wide license.
