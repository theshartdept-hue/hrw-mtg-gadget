# HRW Meeting Companion

A one-page, step-by-step script for hosting Harm Reduction Works meetings: open, focused, and affinity meetings, a pulse check, and pinned announcements.

Open the site, fill in step 1 (your name, tonight's topic, announcements), then use Next or the arrow keys. Settings save on your own device.

HRW format © Albert C. Park & Jessica Tilley 2019 · Adaptation by Paperheart Bureau / Access Point of Georgia

## Live follow-along

The host clicks **Go live**, picks a room name (for example `abcd-sunday`), and pastes the follow link in the chat. Anyone who opens it sees the host's current step, topic, announcements, and pulse counts on their own screen. Host notes never show for followers.

A room belongs to the host who opened it until they end the session, or until it has been idle for 4 hours. Then another host can use the same name, so a weekly meeting can keep one link.

Setup lives in `firebase-config.js` (the web config) and `database.rules.json` (paste into Firebase → Realtime Database → Rules).
