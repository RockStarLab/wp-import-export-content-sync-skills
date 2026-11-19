# WordPress Import/Export Agent Skills

Agent Skills for [Content Sync, Media Sync, Import, Export with AI Agents Support](https://wordpress.org/plugins/import-export-by-rockstarlab/) (free) and its PRO add-on. They teach an AI agent (Claude Code, Claude, Codex, Cursor) to use the plugin's WordPress Abilities API (`rsl-ie/*`, `rsl-ie-pro/*`) instead of clicking through wp-admin.

| Skill | Use for |
|---|---|
| `wordpress-content-sync` | push/pull posts, pages, ACF, comments between two sites |
| `wordpress-import-export` | CSV/XML/JSON/XLSX import and export, mappings, schedules |
| `wordpress-site-migration` | migration ZIP, Media Library and folder sync |
| `woocommerce-sync-pro` | PRO: WooCommerce, CPT, terms, menus, users, tables |

## Install

Claude Code: `/plugin marketplace add <github-user>/<repo>` then `/plugin install wordpress-import-export-skills`.
Other agents: copy the folders from `skills/` into your agent's skills directory.

Requirements: WordPress 6.9+ (Abilities API), the plugin active on every site involved, an administrator application password or the MCP Adapter.

Docs: https://wpimportexport.com
