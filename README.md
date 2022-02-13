![Missouri Outline Logo](https://user-images.githubusercontent.com/43663476/135731754-7144f7a9-fb70-4e79-89e6-f84530451072.jpeg)

# ColumbiaMO Local Telegram Group Docs/Policies

## Attempting to formalize my operation of the [local Telegram group](https://t.me/columbiamo) I created for mid-Missouri.

* [Original thread on the r/ColumbiaMO Subreddit](https://www.reddit.com/r/columbiamo/comments/c4na0v/local_telegram_group_chat_for_columbia/)

## Meta

- **Identification**: -1001227145846
- **Name**: @columbiamo
- **Link**: [https://t.me/columbiamo](https://t.me/columbiamo)
- **Admin**: @[DavidBlue](https://t.me/DavidBlue)

**Description**
Columbia/Mid-Missouri’s (USA) local chat. Be reasonable, please. Bot traffic is currently unallowed. #Rules Documentation here: https://github.com/extratone/columbia

## Rules for Participating in the Columbia Missouri Local Telegram Group

Version 1.1 - `01182022-145328`

View the "original" [rules message in chat](https://t.me/columbiamo/7774) or - more reasonably - prompt Rose to print the most current version any time by sending `/rules` to the chat.

<audio controls>
  <source src="https://github.com/extratone/columbia/raw/main/audio/rulestts.m4a">
</audio>

1. **ColumbiaMO Local Chat** is a place to discuss current events and culture in a friendly, collegial way. We invite you to be smart, kind, welcoming, funny, charming, incisive, prescient, skeptical: whoever you are on your best day.
2. **ColumbiaMO Local Chat** is reserved for people who live, have lived, or intend to live in mid-Missouri as well as travelers through the area. 
3. Share news, opinions, personal experiences, charts, data, photos, tweets, and other media. Do not share misinformation, disinformation, or spam — including in DMs to other members.
4. Do not promote your own hustles — or your clients’ hustles — more than **once per day**.
5. Disruptive off-topic posts (random interjections) are discouraged and unwelcome.
6. Discuss subjects in good faith. Do not troll, mock, or harass other members of the community.
7. Pseudonyms are welcome, and you do not have to disclose where you work, but do not impersonate anyone.
8. Keep it safe for work. **ColumbiaMO Local Chat** is not the place for disturbing images, racy pictures, or anything else you wouldn’t want to share with your coworkers or family.
9. Be inclusive of all people and points of view. This is particularly true for Black, Indigenous, and people of color, and people in the LBGTQ+ community. We will remove any homophobic, transphobic, misogynistic, or racist content without discussion.
10. If someone is bothering you or you would like to report a post or member who you believe is violating these rules, please contact one of the Administrators or Moderators.
11. Final moderation decisions are subject to the whims of the Admins and Mods.
12. We expect to update these rules as necessary. When we do, you’ll see a notification attached to this message.
13. Follow the spirit of these rules as well as the letter of them. Do not become an edgelord. We err on the side of removing borderline content — and borderline users — from the channel.
14. At least for the moment, *automated* sharing of Crypto and sex-related content is a banable offense.


---

## Rose Bot Configuration

```json
{
  "bot_id": 609517172,
  "data": {
    "admin": {
      "admin_error_disable": false,
      "anon_admin": false,
      "legacy_admin": false
    },
    "antiflood": {
      "action": "ban",
      "action_duration": 0,
      "flood_limit": 0
    },
    "blocklists": {
      "action": "mute",
      "action_duration": 0,
      "default_reason": "",
      "filters": [
        {
          "name": "horny",
          "reason": "So sorry, but sex work/solicitation has been at least temporarily banned here until we can figure out what to do about the sex bots lol. Please contact me @DavidBlue if you feel this has happened in error."
        }
      ],
      "should_delete": true
    },
    "disabled": {
      "disabled": null,
      "should_delete": false
    },
    "federations": {
      "fed_id": "6ab78918-b27b-4c33-ae5e-15a109588377",
      "quiet_ban": false
    },
    "filters": {
      "filters": null
    },
    "greetings": {
      "captcha_rules": true,
      "goodbye": {
        "data_id": "",
        "text": "",
        "type": 0
      },
      "kick_after": 0,
      "mute_for": 0,
      "mute_mode": "text",
      "mute_text": "",
      "should_clean": true,
      "should_delete_service": true,
      "should_goodbye": true,
      "should_kick": false,
      "should_mute": true,
      "should_welcome": true,
      "welcome": {
        "data_id": "",
        "text": "Howdy, {mention}! \nWelcome to the Columbia/Mid-Missouri area's local chat group!\nIf you have issues or questions, please bother @DavidBlue, first.\nYou should probably familiarize yourself with these: {rules}",
        "type": 0
      }
    },
    "locks": {
      "allowlisted_url": null,
      "lock_warns": false,
      "locks": {
        "album": false,
        "all": false,
        "anonchannel": false,
        "audio": false,
        "bot": false,
        "button": false,
        "command": false,
        "comment": false,
        "contact": false,
        "document": false,
        "email": false,
        "emojigame": false,
        "forward": false,
        "forwardbot": false,
        "forwardchannel": false,
        "forwarduser": false,
        "game": false,
        "gif": false,
        "inline": false,
        "invitelink": true,
        "location": false,
        "phone": false,
        "photo": false,
        "poll": false,
        "rtl": false,
        "spoiler": false,
        "sticker": false,
        "text": false,
        "url": false,
        "video": false,
        "videonote": false,
        "voice": false
      }
    },
    "notes": {
      "notes": [
        {
          "data_id": "",
          "name": "administrativefederation",
          "text": "`Created new federation with FedID: 6ab78918-b27b-4c33-ae5e-15a109588377.\nUse this ID to join the federation! eg:\n/joinfed 6ab78918-b27b-4c33-ae5e-15a109588377\nSuccessfully joined the \"Extratone\" federation! All new federation bans will now also remove the members from this chat.`\n__Telegram: Contact__ __@extratone__\n__Federation Extratone has now subscribed to Rose Support Official. All fedbans in Rose Support Official will now take effect in both feds.__\nExtratone, [Jan 11, 2022 at 15:37]\nSuccessfully joined the “Extratone” federation! All new federation bans will now also remove the members from this chat.\nExtratone, [Jan 11, 2022 at 15:39]\nFederation Extratone has now subscribed to Rose Support Official. All fedbans in Rose Support Official will now take effect in both feds.\nExtratone, [Jan 11, 2022 at 16:06]\nFederation Extratone has now subscribed to @SpamWatch. All fedbans in @SpamWatch will now take effect in both feds.\nExtratone, [Jan 11, 2022 at 16:06]\nFed info:\nFedID: 1c2221d9-aa27–4baf-b77c-8822b36254d2 Name: @SpamWatch\nCreator: this person (172811422)\nNumber of admins: 1\nNumber of bans: 240233\nNumber of connected chats: 770\nNumber of subscribed feds: 590\nThis federation is not subscribed to any other feds.\nExtratone, [Jan 11, 2022 at 16:06] Admins in federation ‘@SpamWatch’:\n- è Simon | Schu rrle é (172811422)\n • https://t.me/extratone/9658\n • https://t.me/extratone/9659\n • [__Telegram: Contact @extratone__](https://t.me/extratone/9660)\n • [__Telegram: Contact @extratone__](https://t.me/extratone/9661)\n • [__Telegram: Contact @extratone__](https://t.me/extratone/9662) **\n\n*Rose Support Federation Info*\nFed info: FedID: 86718661–6bfc-4bd0–9447–7c419eb08e69 Name: Rose Support Official Creator: this person (254318997) Number of admins: 10 Number of bans: 5951 Number of connected chats: 249 Number of subscribed feds: 361\nThis federation is not subscribed to any other feds.\n*Admins*\nAdmins in federation ‘Rose Support Official’:\n • Dalirena🐮 (2153160)\n • Kees Sonnema (18673980)\n • Andrea (48271100)\n • Harsh Shandilya (211931420)\n • Paul Larsen (254318997)\n • Taylor (260150652)\n • Sebastian (348909717)\n • Glen DeSouza 🎄🐫 (415692419)\n • Kyle (491256848)\n • H 1 (788429389)\n\n*SpamWatch Federation Info*\nFed info: FedID: 1c2221d9-aa27–4baf-b77c-8822b36254d2 Name: @SpamWatch Creator: __this person__ (172811422) Number of admins: 1 Number of bans: 240233 Number of connected chats: 770 Number of subscribed feds: 590\nThis federation is not subscribed to any other feds.",
          "type": 0
        },
        {
          "data_id": "BQACAgEAAx0CSSTCdgACJpVhwQVa2xglZPDg0dczhZpASfFlOQACSAIAArXWCUYRKHsHU1YxtiME",
          "name": "contact",
          "text": "\n",
          "type": 8
        },
        {
          "data_id": "BQACAgEAAx0CSSTCdgACJt1hyIxX6uSW_MbIWr_nvpBD5OzqVwACHAIAAjoWGUZYulI5drv-QSME",
          "name": "mapaper",
          "text": "Here's a zip file of the full-sized images.\n",
          "type": 8
        },
        {
          "data_id": "",
          "name": "rose",
          "text": "Fillings\n\n*Fillings*\n\nYou can also customise the contents of your message with contextual data. For example, you could mention a user by name in the welcome message, or mention them in a filter!\n\n*Supported fillings*:\n- `{first}`: The user's first name.\n- `{last}`: The user's last name.\n- `{fullname}`: The user's full name.\n- `{username}`: The user's username. If they don't have one, mentions the user instead.\n- `{mention}`: Mentions the user with their firstname.\n- `{id}`: The user's ID.\n- `{chatname}`: The chat's name.\n- `{rules}`: Create a button to the chat's rules.\n- `{preview}`: Enables link previews for this message. Useful when using links to Instant View pages.\n\n*Example usages*:\n- Save a filter using the user's name.\n-\u003e `/filter test {first} triggered this filter.`\n- Add a rules button to a note.\n-\u003e `/save info Press the button to read the chat rules! {rules}`\n- Mention a user in the welcome message\n-\u003e `/setwelcome Welcome {mention} to {chatname}!`",
          "type": 0
        },
        {
          "data_id": "BQACAgEAAx0CSSTCdgACKJJh3gXkMa3ccLNdz74GOWA9QysvWwACVQIAAvmb8Ub9c6aee65HeyME",
          "name": "roseconfiguration",
          "text": "",
          "type": 8
        },
        {
          "data_id": "",
          "name": "stickerpacks",
          "text": "1. [2021 Perdition](https://t.me/addstickers/perdition_by_stickersthiefbot)\n2. [GROTESQUE App Icons](https://t.me/addstickers/grotesque_by_stickersthiefbot)\n3. [Extending Emoji](https://t.me/addstickers/ExtendingEmoji_by_stickersthiefbot)\n4. [Extending Emoji II](https://t.me/addstickers/ExtendingEmoji2_by_stickersthiefbot)",
          "type": 0
        }
      ],
      "private_notes": false
    },
    "pins": {
      "antichannelpin": false,
      "cleanlinked": false
    },
    "raids": {
      "raid_mode_action_duration": 3600,
      "raid_mode_duration": 21600
    },
    "reports": {
      "disable_reports": false
    },
    "rules": {
      "button_name": "",
      "content": "# ColumbiaMO Telegram Chat Rules\n\n*Version 1.1 - 2021-11-29-21.15.46*\n\nHello, chat! I’ve finally drafted a presentable copy of the Big Bad Chat Rules.\n\nYou can find a revision-tracked version of this document on the GitHub repo I created, [here](https://github.com/extratone/columbia/blob/main/rules.md).\n\nI have also published [a parallel version](https://telegra.ph/ColumbiaMO-Telegram-Chat-Rules-11-30) of this document to Telegram’s longform service, Telegra.ph.\n\n1. *ColumbiaMO Local Chat* is a place to discuss current events and culture in a friendly, collegial way. We invite you to be smart, kind, welcoming, funny, charming, incisive, prescient, skeptical: whoever you are on your best day.\n2. *ColumbiaMO Local Chat* is reserved for people who live, have lived, or intend to live in mid-Missouri as well as travelers through the area. \n3. Share news, opinions, personal experiences, charts, data, photos, tweets, and other media. Do not share misinformation, disinformation, or spam — including in DMs to other members.\n4. Do not promote your own hustles — or your clients’ hustles — more than *once per day.*\n5. Disruptive off-topic posts (random interjections) are discouraged and unwelcome.\n6. Discuss subjects in good faith. Do not troll, mock, or harass other members of the community.\n7. Pseudonyms are welcome, and you do not have to disclose where you work, but do not impersonate anyone.\n8. Keep it safe for work. *ColumbiaMO Local Chat* is not the place for disturbing images, racy pictures, or anything else you wouldn’t want to share with your coworkers or family.\n9. Be inclusive of all people and points of view. This is particularly true for Black, Indigenous, and people of color, and people in the LBGTQ+ community. We will remove any homophobic, transphobic, misogynistic, or racist content without discussion.\n10. If someone is bothering you or you would like to report a post or member who you believe is violating these rules, please contact one of the Administrators or Moderators.\n11. Final moderation decisions are subject to the whims of the Admins and Mods.\n12. We expect to update these rules as necessary. When we do, you’ll see a notification attached to this message.\n13. Follow the spirit of these rules as well as the letter of them. Do not become an edgelord. We err on the side of removing borderline content — and borderline users — from the channel.\n14. At least for the moment, *automated* sharing of Crypto and sex-related content is a banable offense.",
      "send_to_chat": false
    },
    "translations": {
      "lang": "en-GB"
    },
    "warns": {
      "action": "mute",
      "action_duration": 0,
      "warn_for": 0,
      "warn_limit": 3
    }
  },
  "version": 1
}
```

## Stickers Index

<img src="https://user-images.githubusercontent.com/43663476/150018239-674c140b-1c73-4058-9bf9-3c0e3ac1c95f.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018247-4bae8d40-7bc3-41e8-b7ac-d499a5cc321c.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018248-6a6db3f8-9a65-4bca-802a-0950718c8f28.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018249-c0872537-ae27-40e0-8738-703b9243cc4f.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018252-51e99eb8-b79b-4c9e-a4b8-fa0c5948090a.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018255-91935d69-97fc-4fce-b51e-d00c11db2a20.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018256-8a2f9cd1-2f0f-4f2a-a76a-2d9400585e77.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018258-cb28ba45-6d82-4b04-9a4c-065b43e9dc69.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018259-259e1ecc-318c-4ad5-a641-c2fdfce9bf8e.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018260-c016f576-f389-4ead-9779-c3f7627cf8c7.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018262-6a654ecb-7c3d-4e1e-85da-8c5c49caa6fa.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018263-8edb6b73-a28a-40cc-afb8-770cedcd9f07.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018265-18476f94-ea08-4966-9227-ca78e5c90eed.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018267-311e0df4-0001-4a15-9ecd-fce0d0cf41bd.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018269-ec4deef8-d0f3-4d9e-a5b0-54cd0251bbd3.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018271-6251fb5e-34a1-437a-8b7f-1cbd9f7dc2d8.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018273-1ea9a200-30af-4e29-9eb3-e26b4ef725f9.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018275-3df49fde-2e49-4407-a1b4-10221be61048.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018279-8849bd22-dac8-48b1-8eaf-1a8cafba61d6.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018280-6bbe7e64-2958-4946-9649-57635ddc02bd.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018282-1ef8f818-fcb2-48ce-827d-0a3380dfdccc.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018285-f93b077d-e08b-49e0-99fb-15efa20d9645.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018286-ff4e5008-993d-4126-9e9a-4e9753a4e949.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018287-dd9fa1f9-206b-46df-abc5-16e7e576ead8.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018289-a9c034d7-98f2-4991-b6fc-5f5fe1926f10.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018291-a6cf6b9c-f7a2-45ae-86cf-0dc1d70ad3d8.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018292-e37d6b5c-8612-4236-8cce-b1b355db14c0.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018293-7ae77d88-9164-43b7-9398-b3d27b209101.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018296-7f47e315-4109-448f-aee8-67455f2af5e6.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018298-ea7faab1-9266-4e19-a6ea-00e3379abd21.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018301-224545b0-ce60-4ab4-9070-d62d776b800f.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018303-fa1900a5-e734-446a-8910-345dac66ffe5.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018305-4dc46f29-e285-4e52-9142-6e8aa168b9e7.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018307-d790880b-607a-41a9-a5c1-a0ccec160786.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018309-f263151d-6775-4daf-a954-7886981f82a4.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018312-0b291cd8-d712-4ad9-b117-2f74ada60090.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018314-80f4cade-bf6d-41a8-acc3-021d57fae221.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018316-2b123f1d-c6e7-4f8e-84a4-fe7c38079624.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018319-38d4821e-fa01-4965-8693-f532e97cd343.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018322-c3af71d9-6a8e-4b48-b52a-7a116d2bff6a.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018324-916341ea-59bf-4f01-a2a5-a8c564db2af3.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018325-7f70d858-b795-4ad3-acec-2b5ddead8ef3.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018326-54e40ca5-d83b-4bb6-accd-df3695aafeae.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018328-ce5ef468-4ce6-4ac6-a100-4de896236a8c.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018329-dfbfc9ad-178a-40c0-ac4b-2926c6986357.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018332-3833ebe5-b3a9-4d1a-9222-37fa33c5b9d9.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018333-12af718e-9073-47db-b97b-832ded52ce9c.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018334-6ecdff70-b05b-44b8-9d33-ef2259dc5f1d.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018336-de72bd26-635d-4bb3-96b3-5a692b633bf4.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018338-76f625c7-256e-40f7-8acf-705798a1f4a0.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018340-3c6a4b10-a475-473b-b920-32cb6a079ada.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018341-7d899d49-55a3-4fe8-8b6b-0c9ba36ae9ee.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018342-6e611f21-eb12-45f6-b754-fd93071fa597.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018343-afeed67a-b29b-4492-8faa-ad198474a965.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018344-9e61d2d0-b190-4ab1-ad38-151cfd035770.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018346-c4e88580-8309-499d-addc-88e87aa51101.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018349-44ada526-985b-4aac-918e-85755b6084c2.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018351-7fd28604-19d8-43b6-98dc-1642d694866c.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018352-e947b7c1-eaf1-42cf-a543-f2d94a7e9a94.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018355-6aa0fee6-de4c-40b0-8b1b-da65cf390b0c.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018357-5e4a94a9-c4ab-4109-b6f1-1e3bdcf9ee67.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018358-d2acbbab-e572-4126-b889-d02c7f34ad4c.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018359-290b3761-2d63-494a-97ca-7a0093260d0d.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018362-34e1c626-0e2c-43b8-9044-363bf2db0453.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018366-a720f3df-3e01-4c8c-97e1-b5cde61632ff.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018369-f356eecf-822d-417c-b308-3606c2491130.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018370-4c54d81b-916d-43f9-ae52-45c262d3bb33.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018372-7b1a7a67-0b93-4b7d-a71f-36e9cc7cd096.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018373-20144d3b-1b94-4d21-9ae2-0cb98f14edd5.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018375-f8353db3-59eb-41f9-9859-4cd562b793ee.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018377-c560f76c-a6cb-4f53-9604-e09e5dbadc3e.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018378-443b32ef-5b70-4777-bd96-4dcf95db97f6.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018381-403d5513-8f8f-45ae-8c9a-656c0873b011.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018383-83d1dbab-2fe6-4bbf-9764-ddcd24f8bf14.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018385-39e4cc0f-7d49-456c-bd0d-9c370f6a09aa.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018387-c222c6d3-f790-4cf0-a36c-787133701170.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018388-e5346d0a-8541-4fe9-928f-692ee75faa91.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018389-0594c485-a68a-4612-babe-44a86ca1a3c9.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018390-e81a1ff5-78b9-4d29-a663-2e80dcb86877.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018391-bffed3d1-b731-408d-a9e6-50d2a498c85e.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018392-d0ea6461-34e7-4779-a97e-0e60fdeb36ef.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018393-58bea0de-c975-4ab8-a726-9839e3f06215.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018396-377a17d8-2714-48c2-82c6-e9f9358eb22f.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018398-84ebae5d-62e7-4be4-88bf-4e9819628cfb.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018399-65afcbfa-7584-486c-bc93-668f17cca1e2.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018402-fd11c217-339b-44fa-a2c6-d6f476df90c7.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018403-41c0746f-2dbd-486a-b4ef-fdb7604cfaee.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018404-4a241d3f-6604-42c9-8ff9-7eda7feea1fa.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018405-2f56264e-3d18-4445-90d9-6dd0d1f11138.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018406-2cd4fbf2-b549-487a-a407-71dcaa75632b.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018409-88ea99fd-4f2d-4294-ab15-7a8242e6b4bd.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018411-441e19d7-37c3-46f6-8b4c-5069e63a7cc6.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018412-0609c47b-b00e-4d47-a120-1fadfc0cadda.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018414-71106cf4-002f-4859-96af-b60e80d05ece.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018418-cbac0be2-cd14-4763-b26f-529761cb7821.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018421-bdf706c4-e4ba-4349-bda2-4feafd2d3e48.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018422-f69efc9d-4473-46ba-84c2-65dcea485c6e.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018425-98548f38-1eb8-4c8d-8b23-8b5510e2b9d4.png" width="10%"></img> <img src="https://user-images.githubusercontent.com/43663476/150018429-8288a420-75c5-451b-84fb-3f146d210204.png" width="10%"></img>

1. [**2021 Perdition**](https://t.me/addstickers/perdition_by_stickersthiefbot)
2. [**GROTESQUE App Icons**](https://t.me/addstickers/grotesque_by_stickersthiefbot) 
3. [Extending Emoji](https://t.me/addstickers/ExtendingEmoji_by_stickersthiefbot)
4. [Extending Emoji II](https://t.me/addstickers/ExtendingEmoji2_by_stickersthiefbot)

## Mapaper Images

![mapaper](https://user-images.githubusercontent.com/43663476/147149010-5b770813-f493-4b83-9935-a7b3f12eb268.png)

[**Mapaper**](https://apps.apple.com/us/app/mapaper/id1546487705) is a clever iOS app that was all the rage last year with personal automation nerds. I thought it might be a good Christmas present for the Telegram group, this year, to offer at least a single rendering of the Columbia area in every one of its themes.

Below are a few example images - you can download a [**.zip file of all the images in their full resolution**](https://github.com/extratone/columbia/raw/main/mapaper/mapaper.zip) either here or [in the group, itself](https://t.me/columbiamo/9949).

![ColumbiaMapaper (11)](https://user-images.githubusercontent.com/43663476/147149236-dfc8cd65-c3ed-421a-b2b5-9ed54686d32b.PNG)
![ColumbiaMapaper (12)](https://user-images.githubusercontent.com/43663476/147149238-0c8b9594-00f2-47d5-8943-1d75e8117c69.PNG)
![ColumbiaMapaper (1)](https://user-images.githubusercontent.com/43663476/147149241-b7bea0e9-7355-4abc-a5b0-3bd186d11a09.PNG)
![ColumbiaMapaper (2)](https://user-images.githubusercontent.com/43663476/147149243-20543362-3736-4e2d-bd5c-69d054f012dd.PNG)