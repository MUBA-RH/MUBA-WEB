# MUBA-WEB module map

Architecture source: [MUBA/architecture/06-web-distribution](https://github.com/MUBA-RH/MUBA/tree/main/architecture/06-web-distribution). Active code and deployment remain at their current locations. Listed areas are ownership boundaries, not evidence of an implemented standalone service.

| Area | Responsibility |
| --- | --- |
| [WEBSITE](modules/WEBSITE/CONTENT/README.md) | Module boundary |
| [UPDATE-CENTER](modules/UPDATE-CENTER/CONTENT/README.md) | Module boundary |
| [GALLERY-PUBLIC](modules/GALLERY-PUBLIC/CONTENT/README.md) | Module boundary |
| [STUDIO-PUBLIC](modules/STUDIO-PUBLIC/CONTENT/README.md) | Module boundary |
| [DAILY-STORY-PUBLIC](modules/DAILY-STORY-PUBLIC/CONTENT/README.md) | Module boundary |
| [PUBLISHING](modules/PUBLISHING/CONTENT/README.md) | Module boundary |
| [SOCIAL-LINKS](modules/SOCIAL-LINKS/CONTENT/README.md) | Module boundary |
| [WEBHOOK-HTTP](modules/WEBHOOK-HTTP/CONTENT/README.md) | Module boundary |
| [SMOKE-CHECKS](modules/SMOKE-CHECKS/CONTENT/README.md) | Module boundary |

Each area has CONTENT / UPDATE / TEST / STABLE. See [LIFECYCLE.md](LIFECYCLE.md). No new Render service, Telegram bot, token, key, Vault, or deployment trigger is created here.
