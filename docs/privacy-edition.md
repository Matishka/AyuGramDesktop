# AyuGram Privacy Edition — experimental v0.1.0

Unofficial modification of AyuGram Desktop, based on upstream 0f2a31bb420de98f331990432265b131b8d836b5. Original authors, copyright notices and GPL-3.0 license retained. No affiliation with Telegram or AyuGram maintainers.

Four independent opt-in switches under AyuGram general settings: own phone, others' phones, own username, others' usernames. Masking applies to selected profile/settings display paths, not server data; existing whole-window capture exclusion remains unchanged. Selected alternate usernames, QR and copy handlers are guarded. Other surfaces (search, messages, editing dialogs, preopened menus, notifications, drag/clipboard, cached links) require a separate audit. Do not expose real data on stream until verified.

This branch is a compile candidate, not a production client. No functional API credentials, no migration of tdata, no release or auto-updater changes. TG Tools remains independent. Build workflow is a compile-only experiment; no runnable binary published. Future distribution requires own valid API credentials and GPL compliance. Test isolated data directories with dummy profiles before use.
