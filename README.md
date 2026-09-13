# Briefsmith public sample

**SYNTHETIC SAMPLE — Fictional Example Studio.** This repository demonstrates Briefsmith v1.2.0 output and is not a client project, testimonial, or claim of experience.

Briefsmith converts a small JSON project brief into matching Markdown and standalone HTML files locally. No account, external package, AI service, or network connection is required.

## Browse the demo

- [HTML output](generated/website-accessibility-refresh.html)
- [Markdown output](generated/website-accessibility-refresh.md)
- [Input JSON](project.json)
- [Static browser view](index.html)

## Run it yourself

Use Python 3.9+ with the paid toolkit's `briefsmith.py`:

```bash
python briefsmith.py project.json --output-dir output --strict
```

This public sample intentionally does not include the full paid package. Briefsmith is MIT-licensed; the paid download contains the CLI, tests, two synthetic fixtures, generated examples, README, and license.

## Requirements and limitations

Python 3.9+. The CLI validates the JSON shape and writes local files. It does not host, email, upload, review confidential data, provide legal/content advice, or integrate with external services.

Prepared with AI assistance and tested locally. The tool itself runs without AI services.
