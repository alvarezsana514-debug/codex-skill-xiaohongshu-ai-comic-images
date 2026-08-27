# Security

## Scope reviewed before publication

- No embedded API keys, tokens, passwords, private keys, cookies, or GitHub credentials.
- No shell execution, dynamic code execution, downloaders, telemetry, or outbound network calls in the included Python scripts.
- No file deletion logic.
- Generated index and result files are written only to user-selected project paths.
- Python dependencies are pinned in `requirements.txt`; review them before installation in sensitive environments.

## Credential handling

Set `GLOBALAI_API_KEY` only in the local environment when image generation is needed. Do not place secrets in prompts, project files, commits, issues, or pull requests.

## Reporting

Open a GitHub issue without including secrets or private source material.

