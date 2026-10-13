# Goliath documentation

This repository contains the public Goliath user documentation, published with Mintlify from `main`.

- Write for loader users, not administrators or SDK developers.
- Use concise British English, active voice and the loader's actual UI labels.
- Keep changes simple. Use native Mintlify components and `docs.json` settings.
- Use “licence key”, “Your products”, “Menu updates”, and “Updating / Down”.
- Successful key redemption returns users to Your products. There is no Subscriptions tab.
- Direct users to a seller for resets; sellers handle them through the bot.
- Do not add download, Discord or external support links unless the owner supplies them.
- Do not document screenshot reports; the loader handles that flow.
- Do not publish credentials, real user details, private backend addresses, admin instructions or internal security implementation.
- Error titles, explanations and next steps should match the approved loader wording.
- Every MDX page needs title and description frontmatter and a navigation entry.
- Run `mint validate` and `mint broken-links` before publishing changes.
- Use the configured default build locations. Do not create alternate build folders.
