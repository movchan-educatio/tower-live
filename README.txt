TOWER LIVE — GIFT WARS v2.1 LIVE READY + PWA

WHAT IS NEW
- Installable iPhone/Android PWA: opens from a Home Screen icon in standalone app mode.
- Portrait orientation metadata and iPhone standalone/status-bar metadata.
- Offline app-shell cache via Service Worker.
- Universal public event entry point:
    window.receiveLiveEvent(event)
    window.receiveTikTokGift(event)
- Normalizes username, giftName, giftId, count/repeatCount, coinValue/value and eventId.
- Event ID de-duplication with bounded/expiring cache.
- Gift mapping by known gift name/id, with value-tier fallback.
- Count is safely capped per event.
- Existing v2.0 visuals, music, destruction, leaderboard, combo and CHAOS systems retained.

EXAMPLE EVENT
receiveLiveEvent({
  eventId: "evt-123",
  username: "@viewer",
  giftName: "Rose",
  giftId: "rose",
  count: 5,
  coinValue: 1
});

IMPORTANT
This package does NOT contain or invent an unofficial TikTok endpoint.
Real TikTok LIVE events still require an approved/compatible TikTok LIVE Interactive Games integration or bridge.

INSTALL ON IPHONE
1. Host these files over HTTPS (your existing GitHub Pages is sufficient).
2. Open the game URL in Safari.
3. Share -> Add to Home Screen -> Add.
4. Launch TOWER LIVE from its icon.
After the shell is cached, the prototype can reopen offline; real LIVE events require internet.

UPDATE
When replacing an older hosted version, upload ALL files in this folder, not only index.html.
