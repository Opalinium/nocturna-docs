# Privacy Policy for Nocturna

**Effective Date:** October 1, 2025  
**Last Updated:** March 8, 2026

This Privacy Policy explains what information Nocturna collects and how we use it.

## What We Collect

**To make the bot work, we collect:**
- Discord user IDs, usernames, and server information
- Message IDs and timestamps for moderation logs
- Message content for logging and moderation, subject to per-user privacy controls via `/privacy`
- Voice channel activity (join/leave times)
- Invite usage and role assignments
- Commands you use and buttons you click
- Game/application activity presence data (game names, session durations, session counts, and related user IDs) when the game metrics feature is enabled in your server
- Experience points (XP), level progression, and rank card customization data when the levelling feature is enabled in your server
- Starboard message records (starred message IDs, channel IDs, reaction counts) when starboard is configured in your server
- Vote history, vote streak data, and vote reminder preferences when you use the `/vote` command or vote on Top.gg

**Information you provide:**
- Moderation case notes and reasons
- Custom tags, commands, and server settings
- Reminders and scheduled content
- Custom branding preferences (premium feature)
- Automatic nickname patterns and role exclusions (premium feature)
- Ticket system configurations and support roles
- Welcome and goodbye message configurations (premium feature)
- Anti-spam configuration thresholds and exemption lists

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
- Track game/application activity for server-level metrics (opt-in per server)
- Support per-user privacy controls, including message and game presence tracking opt-out with anonymized aggregation where applicable
- Maintain levelling and XP progression records
- Record and display starred messages on the starboard
- Deliver vote-based temporary premium access and vote reminders (Top.gg integration)
- Maintain accurate bot blacklist records to enforce access restrictions
- Post aggregate server statistics (server count only, no personal data) to Top.gg

## Data Storage and Deletion

**How long we keep data:**
- Moderation logs: Until you delete them
- Voice activity: 7 days
- Message content: Deleted when message is deleted from Discord, or automatically after 1 year (365 days for free servers, 730 days for premium servers). Message tracking opt-out settings are respected
- Media thumbnails: 30 days for free servers, 730 days for premium servers
- Invite tracking: 30 days
- Your settings/tags: Until you delete them
- Premium subscription data: Duration of subscription plus 90 days after expiration
- Custom branding settings: Duration of premium subscription
- Archived anti-raid custom patterns: 3 months after premium expires
- Ticket transcripts: Retained within the ticket thread; staff may delete archived tickets if needed
- Game/activity metrics: Stored indefinitely while the metrics feature is active; deleted on server request. Users who opt out of game presence tracking are represented as anonymous in aggregate metrics where applicable
- Levelling/XP data: Stored indefinitely while the levelling feature is active; deleted on server or user request
- Starboard records: Stored while starboard is configured; deleted on server request
- Vote history and vote streak data: Stored indefinitely to maintain accurate streak records
- Vote preferences (e.g., reminder opt-in): Stored until you change them or request deletion
- Blacklist records: Retained indefinitely or until the blacklist entry is manually removed by an administrator

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
- **Top.gg:** Bot listing and vote-based premium. We send server count (aggregate, not personal data) to Top.gg periodically, and receive vote webhook notifications containing your Discord user ID when you vote for the bot. Subject to Top.gg's Privacy Policy.
- **PostgreSQL/Redis:** Secure database hosting for data storage

You should review the privacy policies of these services as they have their own data handling practices.

## Age Requirement

You must be 13+ to use Discord and this bot (or 16+ in some jurisdictions). We do not knowingly provide services or process data for anybody under the applicable age requirement.

## Data Location and Security

**Data storage:**
- Data is stored on secure servers
- Sensitive fields are encrypted at the application layer before being written to the database, using Fernet (AES-128-CBC + HMAC-SHA256). Encrypted fields include message content, author names, moderation case reasons, mute reasons, reminder messages, rank card bios, and metrics game names. Certain operational identifiers (such as Discord user IDs, guild IDs, and channel IDs) are stored in plaintext where required for core bot functionality and relational integrity
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
- Disable metrics, levelling, or starboard features to stop new data collection

**All users can:**
- Delete their own reminders
- Block the bot to stop DMs
- Request info about their stored data
- Disconnect their Patreon account
- Request deletion of their premium subscription data
- Opt out of game/activity/message tracking via `/privacy`
- Opt out of vote reminders via `/vote reminder`
- Request deletion of their levelling/XP data
- Request deletion of their vote history

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
3. For personal data: Provide your user ID
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