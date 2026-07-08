# GitHub Banner Logo Prompt

A minimal wrapper for generating a GitHub social preview / README banner from two inputs:

1. a GitHub repository URL
2. a reference-board image for style

The full prompt lives in [`prompt.md`](prompt.md). Replace:

```md
{{GITHUB_REPOSITORY_URL}}
{{REFERENCE_BOARD_IMAGE}}
```

then send the prompt to an agent or image generator.

## Example

| Reference board | Generated banner |
|---|---|
| ![Reference board](/var/folders/72/4xflf9vn3szd81nsycnp8hd40000gn/T/codex-clipboard-4efee35f-0af2-48b4-b553-1992840e8ba9.png) | ![Generated banner](/var/folders/72/4xflf9vn3szd81nsycnp8hd40000gn/T/codex-clipboard-72a3456e-daf8-4439-986c-57b40f5c3a06.png) |
| ![Reference board](/var/folders/72/4xflf9vn3szd81nsycnp8hd40000gn/T/codex-clipboard-3b4fa9f8-c841-4ddc-9a2f-2d48a85caec4.png) | ![Generated banner](/var/folders/72/4xflf9vn3szd81nsycnp8hd40000gn/T/codex-clipboard-a0aedfbd-1aa1-496a-9804-4d4cda158f50.png) |

## Usage

```md
Repository:
https://github.com/user/project

Reference board:
attached image
```

The agent should then:
- inspect the repository
- keep repository content separate from reference-board style
- describe the visual concept first
- generate a 1280x640 banner
