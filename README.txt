TOWER LIVE BATTLE v1.3 FIXED

Critical fix:
- All bottom buttons now use explicit DOM references and addEventListener.
- The previous build had a JavaScript naming collision: the `gifts` data array shadowed the GIFTS button id, so the tap handler was attached to the array instead of the button.
- Gift menu, DROP, ROUND, sound and NEXT ROUND are wired independently.

Visual/gameplay upgrades:
- The unexplained thin bottom line is replaced with a clearly styled TOWER BASE platform.
- Crown, Rocket and Universe now have premium incoming effects.
- Universe opens a purple portal-like ring.
- Rocket has an incoming trail plus its existing exhaust.
- Crown gets a gold entrance ring.
- Crown/Universe destruction shockwaves have unique styling.
- Unique gift silhouettes, damage stages, HP strips, rotating debris, sparks, impact flash, screen shake and original background music remain.
- Controls have explicit z-index and mobile touch-action handling.

TikTok LIVE gift events are still simulated in this prototype.
