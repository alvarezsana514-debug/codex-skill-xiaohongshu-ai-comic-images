# xiaohongshu-ai-comic-images

Portable Codex skill for knowledge-grounded Xiaohongshu AI comic image copy and reference-guided image generation.

## Install

Ask Codex to install this public GitHub skill URL:

```text
https://github.com/alvarezsana514-debug/codex-skill-xiaohongshu-ai-comic-images/tree/main/skills/xiaohongshu-ai-comic-images
```

Or use the bundled skill installer directly:

```bash
python3 "$CODEX_HOME/skills/.system/skill-installer/scripts/install-skill-from-github.py" \
  --url https://github.com/alvarezsana514-debug/codex-skill-xiaohongshu-ai-comic-images/tree/main/skills/xiaohongshu-ai-comic-images
```

Install the Python helpers' pinned dependencies only if they are missing:

```bash
python3 -m pip install -r "$CODEX_HOME/skills/xiaohongshu-ai-comic-images/requirements.txt"
```

Image generation additionally requires the `gpt-image-2-http` skill and a locally configured `GLOBALAI_API_KEY`. Never commit the key to this repository.

## Security

The published files exclude local knowledge-base content, reference images, generated images, credentials, `.DS_Store`, caches, and machine-specific user paths. See [SECURITY.md](SECURITY.md).

