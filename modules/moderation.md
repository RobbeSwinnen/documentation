---
order: 800
icon: dot-fill
label: Moderation
author:
  name: Robbe
  avatar: https://cdn.discordapp.com/attachments/1034201179716079777/1084940308686589992/Robbe.png
tags: [module]
---

Welcome to the Moderation feature of Sapphire! Our advanced system is designed to help you easily manage user behavior on your server. In this guide, we will cover everything you need to know about the Moderation system and how to use it effectively.

---

### Cases

The Cases module displays every case of all punished users. Each case includes all the necessary information about the punishment. When you punish a user, a case is created, and you can view all cases using the s!cases command or by navigating to Moderation -> Cases inside the dashboard.

To view a case of a specific user, type s!caseinfo [case id] or s!cases [user] for a list of all cases with that user. The [user] argument refers to an @mention or the user ID.

If a case is temporary, it will expire when the punishment time is up. However, if a case is permanent, it will remain in the user's profile as open. You can close and delete cases at any time, but note that deleting a case will not unpunish the user.

---

### Edit and Close Cases

Cases can be edited and closed at any time. To edit a case using a command, type s!case [case id] or s!caseupdate [user id]. This will display the case's information, and you can edit the reason, length, proof, and moderator note. To close the case, click on the "Close" button next to the Edit button, or type s!closecase [case id] [reason]. If you click on "View full case," the case will open in the browser.

It is also possible to edit multiple cases at once. To do this, click on "Mass edit," select all the cases you want to edit, and then choose an action. The same actions will be displayed there.

---

### Punish Settings

The punish settings allow you to configure default values for punishments. This includes the default reason, internal reason (visible for Discord's audit-log and other bots), default duration, and actions on punish that will be executed. You can also force the moderator to include a reason when punishing a user.

For mutes, you can link mutes with Discord's timeouts and extend the timeout. Timeouts are limited to 28 days, but Sapphire can extend them hourly. The "Allow multiple" option allows a user to have multiple mutes at once. The "Reply to message to punish" option allows you to reply to a user's message with a punish command to punish them. The argument for the username is not required then, and the user's message will be used as verified proof.

---

### Immune Roles

You can set roles that should be immune to all or specific types of punishments, including bans, kicks, mutes, and warns. All roles listed in this module cannot be punished by a user.

---

### User Notifications

You can enable or disable direct message notifications for users who get punished and unpunished by Sapphire and through another bot/user (the moderator).

---

### Predefined Reasons

You can define reason aliases for punishments. This means that when you set "ads" or "r1" as an alias and "Self-promotion or advertising in chat or direct messages" as the predefined reason, you can punish a user with "ads" as a reason to include/display the reason you defined. For example, s!mute @SomeUser 6h ads will mute the user for 6 hours with the reason "Self-promotion or advertising in chat or direct messages."

---

### Channel Locking

With this feature, you can set up channels that will be locked after using the s!lockall command. The lockall command locks all selected channels. The "Ignored roles" option lets you add roles that will be ignored from locking.

---

### Privacy

Protecting user privacy is of utmost importance in any application. As such, it is essential to decide what case information is displayed to users.

To clarify, "command output message details" refer to the message that is sent to users after a punish command has been successfully executed. This message typically includes the username and user ID of the affected user, as well as the type of punishment that was administered (e.g., "User#1000 has been banned").

On the other hand, "direct message details" pertain to the information message sent directly to the user via direct message. This message typically informs the user of the type of punishment they have received (e.g., "You have been muted").

By being mindful of what information is displayed to users, you can ensure that user privacy is maintained, and users feel secure in using your application. Remember to carefully consider which details are necessary to display, and which can be withheld without impacting the user experience.