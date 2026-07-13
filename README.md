# Codex Pets

This repository is a collection of custom Codex pets that I make with Codex for
my personal use and to share with friends and family.

Each pet can have its own artwork, personality, and animations. This repository
is where I keep and develop those creations.

To learn more about pets and how they work in Codex, see the
[official Codex Pets documentation](https://learn.chatgpt.com/docs/pets?surface=app).

## Repository layout

Codex loads the active pets from `~/.codex/pets/<pet-id>/`. This repository
keeps the corresponding source artwork, animation frames, QA artifacts, and
validated spritesheets as backups:

- `blu/` backs up the installed `~/.codex/pets/blu/` pet.
- `lua/` backs up the installed `~/.codex/pets/lua/` pet.
