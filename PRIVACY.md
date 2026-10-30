# Erix Privacy Policy

Last updated: 30 October 2026

Erix ("the bot", "we") is a Discord moderation and community-management bot. This policy explains what data the bot uses and how to ask us to delete it. Contact details are at the bottom.

## 1. What we collect and why

| Data | Why | Stored? |
|---|---|---|
| Server (guild) ID and settings: prefix, AutoMod configuration (enabled modules, actions, limits, bad-word list), whitelists, log channel, welcome message setup, premium status | To remember each server's configuration | Yes |
| User ID | Invite tracking and leaderboards, whitelists, giveaways, timers, polls, premium status | Yes |
| Invite data: which inviter a member joined through, join time, whether the account was new/fake, rejoins | Invite log and invite leaderboards | Yes |
| Moderation logs: server ID, target user ID and tag, action taken, reason, channel ID, time | Server moderation history and the AutoMod log channel | Yes |
| Message counts per user (a number only, never the text) | Message leaderboards | Yes |
| Giveaway and timer data (IDs, end times, participants) | To run giveaways and timers | Yes, until they end or are deleted |

## 2. Message content
Erix reads message text in servers where an administrator has enabled AutoMod, and to detect prefix commands. AutoMod checks each message for Discord invite links, words from the server's bad-word list, and excessive capital letters, then applies the action the administrator configured. **Message content is processed in memory only and discarded immediately. We do not store, log, sell, analyse, or share message content, and we never use it to train machine learning or AI models.** Moderation logs keep only IDs, the action and the reason, never the message text. Server administrators can exempt users, roles or channels from AutoMod with the whitelist.

## 3. Server member events
The bot receives member join events to send the welcome message a server administrator configured, and to work out which invite a member used so the inviter is credited in the invite log and leaderboard. We use the user ID, account creation date and join time. We do not collect presence, status, or activity data.

## 4. What we do not do
- We do not sell or share data with advertisers, data brokers, or third parties.
- We do not profile users or track them outside Discord.
- We do not collect passwords, tokens, or payment details.
- We do not knowingly collect data from anyone under 13 (or the minimum age in your country).

## 5. Where data is stored and how it is protected
Data is stored on MongoDB Atlas. We restrict access to the database and protect it with access credentials. Atlas encrypts cluster storage at rest using its cloud provider's volume-level encryption, and data in transit is protected with TLS. We do not keep data longer than needed for the features above.

## 6. Retention and deletion
- Server settings are removed when the bot is removed from a server and you ask us to delete them.
- Invite data, moderation logs and counters stay until you ask us to delete them. You can also reset your own invite data with the bot's invite reset commands (for example `resetmyinvites`).
- To request deletion of your data, contact us using the details below and include your Discord user ID. We delete it within 30 days.

## 7. Changes
We may update this policy. The date at the top shows the latest version.

## 8. Contact
- Support server: https://discord.gg/a5cYS2BTfZ
