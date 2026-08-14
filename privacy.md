# Privacy Policy for Nocturna

**Effective Date:** October 1, 2025  
**Last Updated:** August 14, 2026

This Privacy Policy explains what information Nocturna collects and how we use it.

## What We Collect

**To make the bot work, we collect:**
- Discord user IDs, usernames, and server information
- Message IDs and timestamps for moderation logs
- Message content for logging and moderation, subject to per-user privacy controls via `/privacy`
- Voice channel activity: join/leave events are written to your server's configured log channel, and when the metrics feature is enabled, voice sessions (channel ID, start and end time, and session duration) are also stored for server statistics
- Invite usage and role assignments
- Commands you use and buttons you click
- Server statistics data when the metrics feature is enabled in your server: voice session records, per-channel message counts, member join/leave events, and time-to-membership figures
- Experience points (XP), level progression, and rank card customization data, including any custom background image you upload, when the levelling feature is enabled in your server
- Starboard message records (starred message IDs, channel IDs, reaction counts) when starboard is configured in your server
- Vote history, vote streak data, and vote reminder preferences when you use the `/vote` command or vote on Top.gg
- A snapshot of your roles when you leave a server with the Restore Roles feature enabled, so they can be reapplied if you rejoin
- Your pending verification status (and its expiration) while your server's verification feature is processing your membership
- Raid-detection data (member counts, name-pattern clusters, account-age patterns) captured when anti-raid protection mitigates a suspected raid
- Giveaway entries and winner records when you enter a giveaway hosted with the Bot

**Information you provide:**
- Moderation case notes and reasons
- Custom tags, commands, and server settings
- Personal tags you create with `/tag`, which follow your account across every server you use the Bot in
- Reminders and scheduled content
- Your AFK status message, set via `/afk`
- Your birthday (month and day), if you choose to register it
- Highlight keywords and ignore lists you configure to get notified when they're mentioned
- Custom branding preferences (premium feature)
- Automatic nickname patterns and role exclusions (premium feature)
- Ticket system configurations and support roles
- Welcome and goodbye message configurations (premium feature)
- Anti-spam configuration thresholds and exemption lists
- Your personal language preference and custom text overrides via `/language personal`

**Administrative records we maintain:**
- Bot blacklist records: if a user or server is blacklisted from using the bot, we store the relevant Discord ID, the reason, the date of blacklisting, and the ID of the administrator who applied it. This data is retained indefinitely unless the blacklist entry is manually removed.

**Premium subscription information:**
- Patreon user IDs (if you're a patron)
- Subscription status and tier level (Personal, Basic, Plus, or Pro)
- Discord account linked to your Patreon account
- Premium guild associations and activation history
- Subscription start and expiration dates
- Guild activation count per tier

## How We Use Your Data

We use this information only to:
- Make the bot function (commands, moderation, logging)
- Track server events and member activity
- Store your custom configurations and settings
- Manage premium subscriptions and feature access
- Verify Patreon supporter status
- Apply custom branding (premium feature)
- Produce server-level activity and retention statistics (opt-in per server)
- Support per-user privacy controls for message tracking via `/privacy`
- Maintain levelling and XP progression records, including custom rank card assets
- Record and display starred messages on the starboard
- Deliver temporary Personal-tier user vote perks and vote reminders (Top.gg integration)
- Maintain accurate bot blacklist records to enforce access restrictions
- Post aggregate server statistics (server count only, no personal data) to Top.gg
- Restore your roles if you rejoin a server with Restore Roles enabled
- Verify new members before granting server access, where your server uses the verification feature
- Detect and mitigate raid activity
- Notify you when a keyword you're highlighting is mentioned
- Run giveaways and select winners
- Apply your personal language and text preferences to messages the Bot sends you, unless your server has restricted this via `/language config`

## Data Storage and Deletion

**How long we keep data:**
- Moderation logs: Until you delete them
- Voice session records (metrics feature): Stored indefinitely while the metrics feature is active; deleted on server request or when the Bot is removed from your server
- Message content: Deleted when message is deleted from Discord, or automatically after 1 year (365 days for free servers, 730 days for premium servers). Message tracking opt-out settings are respected
- Media thumbnails: 30 days for free servers, 730 days for premium servers
- Invite tracking: Retained indefinitely while the Bot remains in your server, used to attribute new-member joins to the referring invite; deleted when the Bot is removed from your server
- Your settings/tags: Until you delete them
- Premium subscription data: Duration of subscription plus 90 days after expiration
- Custom branding settings: Duration of premium subscription
- Archived anti-raid custom patterns: 3 months after premium expires
- Ticket transcripts: Retained within the ticket thread; staff may delete archived tickets if needed
- Other metrics data (channel message counts, member join/leave events): Stored indefinitely while the metrics feature is active; deleted on server request or when the Bot is removed from your server
- Levelling/XP data: Stored indefinitely while the levelling feature is active; deleted on server or user request
- Starboard records: Stored while starboard is configured; deleted on server request
- Vote history and vote streak data: Stored indefinitely to maintain accurate streak records
- Vote preferences (e.g., reminder opt-in): Stored until you change them or request deletion
- Blacklist records: Retained indefinitely or until the blacklist entry is manually removed by an administrator
- AFK status: Until you send a message (which automatically clears it) or clear it manually
- Birthdays: Until you or a server administrator remove it
- Personal tags: Until you delete them
- Highlight keywords and ignore lists: Until you remove them
- Restore Roles snapshots: From when you leave a server until you rejoin (your roles are then reapplied and the snapshot deleted), or until a server administrator removes it
- Verification queue entries: Until you complete or fail verification, or automatically one day after expiration
- Anti-raid fingerprint records: Retained indefinitely for security auditing; deleted on server request
- Giveaway entries and winner records: 30 days after the giveaway ends
- Personal language preference and custom text overrides (`/language personal`): Until you reset or delete them

**Important:** If you remove the bot from your server, your data stays in our database. To delete it, contact us with your server ID and we'll remove it within 30 days.

## Patreon Integration

**When you connect your Patreon account:**
- We access your Patreon profile to verify your supporter status
- We use OAuth2 authentication (you authorize access through Patreon)
- We store your Patreon user ID to link your Discord and Patreon accounts
- We periodically check your subscription status to maintain premium features
- We do not access your payment information or financial details

**What we receive from Patreon:**
- Your Patreon user ID
- Your supporter tier/level (Personal, Basic, Plus, or Pro)
- Your subscription status (active/inactive)
- Your Discord account connection (if linked on Patreon)
- Subscription tier change history (for enforcement of guild limits)

**You can revoke our access** at any time through your Patreon account settings. This will disable premium features but will not delete stored data unless you request deletion.

## Data Sharing

**We don't share your data.** We don't sell it, give it to advertisers, or use it for marketing.

**The only exceptions are:**
- If required by law (legal obligation)
- Patreon API integration (to verify your supporter status)
- Service providers necessary for bot operation (hosting, database)

**We do not share:**
- Your premium subscription status with other users
- Your Patreon information with Discord (beyond what Discord already has)
- Any personally identifiable information with third parties
- Guild activation information between server owners

**Automated notifications:**
- Server owners may receive a notification when someone activates premium in their server
- Users receive notifications when their guilds are automatically deactivated due to tier downgrades
- These notifications contain only the guild name and activation status, no personal data

## Third-Party Services

**We integrate with:**
- **Discord:** Primary platform (subject to Discord's Privacy Policy)
- **Patreon:** Premium subscription verification (subject to Patreon's Privacy Policy)
- **Top.gg:** Bot listing and vote-based perks. We send server count (aggregate, not personal data) to Top.gg periodically, and receive vote webhook notifications containing your Discord user ID when you vote for the bot. Vote perks are user-scoped and do not activate server-level premium. Subject to Top.gg's Privacy Policy.
- **PostgreSQL/Redis:** Secure database hosting for data storage

You should review the privacy policies of these services as they have their own data handling practices.

## Age Requirement

You must be 13+ to use Discord and this bot (or 16+ in some jurisdictions). We do not knowingly provide services or process data for anybody under the applicable age requirement.

## Data Location and Security

**Data storage:**
- Data is stored on secure servers
- Sensitive fields are encrypted at the application layer before being written to the database, using Fernet (AES-128-CBC + HMAC-SHA256). Encrypted fields include message content, author names, moderation case reasons, mute reasons, reminder messages, and rank card bios. Certain operational identifiers (such as Discord user IDs, guild IDs, and channel IDs) are stored in plaintext where required for core bot functionality and relational integrity
- Database access is restricted and monitored
- We use industry-standard security practices

**Data processing:**
- We process data based on legitimate interest to provide bot services
- Premium data is processed based on contractual necessity
- We implement appropriate technical and organizational security measures

**While we take security seriously, no system is 100% secure.** You acknowledge that you provide data at your own risk.

## Policy Updates

We may update this policy. Material changes will be announced in our support server and reflected in the "Last Updated" date above.

Continued use of the bot after changes constitutes acceptance of the updated policy.

## Your Rights

**Server administrators can:**
- Delete moderation cases and server data
- Configure what gets logged
- Request full data deletion
- Revoke premium features from their server
- View their stored branding settings
- Disable metrics, levelling, starboard, restore roles, verification, or anti-raid features to stop new data collection
- Restrict members' personal language/text preferences from applying in their server via `/language config`

**All users can:**
- Delete their own reminders
- Block the bot to stop DMs
- Request info about their stored data
- Disconnect their Patreon account
- Request deletion of their premium subscription data
- Opt out of message tracking via `/privacy`
- Opt out of vote reminders via `/vote reminders`
- Request deletion of their levelling/XP data
- Request deletion of their vote history
- Clear their own AFK status, birthday, personal tags, and highlight keywords at any time
- Reset their personal language preference and text overrides via `/language personal`

**Premium subscribers can:**
- View their subscription status via bot commands
- Revoke Patreon access through Patreon settings
- Request deletion of Patreon-linked data
- View which servers have premium activated
- Manage their guild activations within tier limits

## Data Deletion Requests

To request deletion of your data:

1. Join our support server: https://discord.gg/VjbkYtDxZf
2. For server data: Provide your server ID and confirm you're a server admin
3. For personal data (including AFK status, birthday, personal tags, and highlights): Provide your user ID
4. For Patreon data: Provide your Discord ID and Patreon email
5. For vote/levelling/metrics data: Specify the data type and provide your user ID or server ID

We will process deletion requests within 30 days.

**Note:** Some data may be retained for legal compliance, fraud prevention, or enforcement of our Terms of Service (including blacklist records). Blacklist records are maintained at our sole discretion and are not subject to user deletion requests.

## Contact Us

Questions or want to delete your data? Join our support server: https://discord.gg/VjbkYtDxZf

For privacy-specific inquiries, you can contact us through the support server with the subject line "Privacy Inquiry."

---

*By using Nocturna, you agree to this privacy policy.*

---

© 2026 Nocturna. All Rights Reserved.

This Privacy Policy document is specific to the Nocturna Discord bot. Unauthorized copying or use of this document is prohibited.