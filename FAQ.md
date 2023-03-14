---
label: "FAQs"
icon: unverified
order: 550
author:
  name: Robbe
  avatar: https://cdn.discordapp.com/attachments/1034201179716079777/1084940308686589992/Robbe.png
tags: [faqs]
---
## General Questions
- What is custom branding?
- What is the difference between banAdd and guildBanAdd?
- The difference between the "Delete all" and "Delete overflow" options in our system. Let us explain it in simple terms.
- Difference Between Caseclose and Unpunish Command
- What is proof and verified proof?

**What is custom branding?**

So, what exactly is Custom Branding? It's a fantastic feature that allows you to personalize your bot in a way that suits your needs. With Sapphire, you can customize your bot's name, avatar, status, and about me section. This means you can tailor the bot's appearance and persona to match your brand's image and tone.

But that's not all. With Custom Branding, you get an entire bot that's hosted just for you. This means you have exclusive control over your bot and its features. And the best part? It starts at just €5 per month. With this, you get access to everything Sapphire offers, including a completely customizable bot's appearance.

If you want to learn more about how Custom Branding can benefit your business, head over to https://sapph.xyz/custom-branding. there's a wealth of information that can help you make an informed decision.

---

**What is the difference between banAdd and guildBanAdd?**

If you're new to moderating a server, you might be wondering what the difference is between the log types banAdd and guildBanAdd. Both log types are related to banning a user, but they provide different levels of information.

Firstly, let's take a look at banAdd. This log type is triggered when a new moderation case is created, and it sends the default message logBan. The logBan message contains all the necessary information that an admin needs to know about the user who has been banned. This information includes proof, verified proof, duration, reason, name, user ID, and case ID. As you can see, this log type provides a comprehensive overview of the ban, making it easy for admins to keep track of moderation cases.

On the other hand, guildBanAdd is triggered when someone has been banned from the server. This log type provides less information than banAdd, and the message logguildbanadd only includes the name, user ID, and reason for the ban. Although this log type provides less information, it is still useful for keeping track of banned users.

It's also worth noting that both log types will be triggered if you have the feature enabled and someone is banned from the server. However, guildBanAdd will only be triggered for bans that are not part of a moderation case.

We hope this explanation helps you understand the difference between banAdd and guildBanAdd. If you have any further questions or concerns, please don't hesitate to contact us.

---

**The difference between the "Delete all" and "Delete overflow" options in our system. Let us explain it in simple terms.**

"Delete all" option will delete every message that triggers the condition, from the first message to the last. For example, if you set your Spam condition to ≥ 5 messages in 10 seconds with "Delete all" enabled, it will delete every message from the first message that triggered the condition to the last.

On the other hand, "Delete overflow" option will only delete the messages that exceeded the condition, which means the messages that triggered the condition after the threshold has already been reached. For instance, if someone sends 10 messages while only 5 are allowed, the bot will only delete the last 5 messages that exceeded the condition.

---

**Difference Between Caseclose and Unpunish Command**

If you're wondering about the difference between caseclose and unpunish commands when it comes to handling user punishments, this article is for you!

Firstly, the caseclose command is used to close a specific case by its unique case ID. To execute this command, simply type s!caseclose <case id> [reason]. This is particularly useful when you want to close only one specific case.

On the other hand, unpunish commands (unwarn, unban, and unmute) are designed to close all open/active cases of a user from the same type of punishment. For example, using s!unwarn @Xge will close all open warnings for the user Xge, which is a helpful solution when you want to close multiple cases at once.

In summary, the main difference between these two commands is that caseclose is used to close a specific case by its unique ID, while unpunish commands close all open cases of the same punishment type for a specific user. Now that you know the difference, you can choose which command to use depending on your needs.

---

**What is proof and verified proof?**

Proof is evidence that supports a moderation case. You can manually add proof to a case by using the s!setproof [proof] command or by editing an existing case and entering new proof. This helps moderators keep track of important information and make informed decisions.

Verified proof, on the other hand, is proof that is added automatically by our system. When a user triggers the auto-moderation module and condition, Sapphire adds verified proof to the case to confirm that the user did indeed write the flagged word or phrase.

If you want to contribute to the verification process, you can also use the "Reply to message to punish" feature. Simply reply to a message with a punish command, such as s!warn, and the user's message will be used as verified proof. Please note that this feature must be enabled under Moderation -> Punish settings.