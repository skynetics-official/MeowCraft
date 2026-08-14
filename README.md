# 🐱 MeowCraft

MeowCraft is a Windows Minecraft launcher focused on simple modpacks, mods and easy sharing with friends.

## Planned / current features

- Minecraft releases, snapshots and older versions
- Vanilla, Fabric, Forge and custom installations
- Ely.by account support with browser OAuth/PKCE work in progress
- Microsoft account support
- Modrinth mod browser
- Custom `.jar` mods
- Modpack creation/import/export
- Russian and English UI
- Automatic RAM detection
- Hidden Minecraft console option
- GitHub-based launcher updates
- Automatic Windows builds through GitHub Actions

## Development

Requirements: Node.js 22 LTS and Java appropriate for the selected Minecraft version.

```bash
npm ci
npm start
```

Build Windows installer:

```bash
npm run build
```

## Releases

Push a tag such as `v3.5.0` to build and publish the Windows installer automatically.

## Ely.by

Public desktop Client ID: `meowcraft1`. Passwords must never be stored in the repository. Browser authorization is being implemented as a public desktop OAuth client with PKCE.
