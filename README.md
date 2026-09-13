# Zotero Library

This directory is written by the [Zotero GitHub Sync](https://github.com/situkangsayur/zotero-github-plugin) plugin. Edits made here are not read back into Zotero unless you run **Import from GitHub**.

## Libraries

- [My Library](my-library/index.md) — 6 item(s), 0 collection(s)

## Layout

| Path | Contents |
| --- | --- |
| `<library>/items/<KE>/<KEY>.json` | One file per top-level item: Zotero API JSON for the item and all its notes, attachments and annotations |
| `<library>/notes/<A>/*.md` | Markdown with YAML front matter, readable in Obsidian |
| `<library>/collections.json` | Every collection and its full path |
| `<library>/searches.json` | Saved searches |
| `<library>/settings.json` | Tag colors |
| `<library>/index.md` | Table of contents grouped by collection |
| `<library>/attachments/<KE>/<KEY>/` | Attachment files |
| `<library>/attachments-lfs/<KE>/<KEY>/` | Large attachment files, stored with Git LFS |

Large files are stored with [Git LFS](https://git-lfs.com). Install it before cloning, or those files check out as small pointer files.
