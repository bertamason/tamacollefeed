
# recordName

> This is the feed's ID which can be letters, numbers, or dashes. Spaces are not allowed. Maximum length is 15 characters.

tamacolle-kw

# displayName

> This is the title of the custom feed. Maximum length is 24 characters.

HT V2

# description

> This is the description of the feed.


# searchTerms

> There are three types of search terms:
>
> - Keywords: Test these in [https://bsky.app/search](https://bsky.app/search). `AND` is implicit, so `cat dog` on one line will require both `cat` and `dog`. You can use quotes as well `"hot dog"`.
> - Users: links such as `https://bsky.app/profile/why.bsky.team` will pull in the user's posts. To include replies and reposts, you can add the following flags: `https://bsky.app/profile/why.bsky.team +replies +reposts`.
> - Pinned posts: links such as `https://bsky.app/profile/saddymayo.bsky.social/post/3jxju2wwap22e` will pin at the top of the feed. One link per line, please.

- "魂これ"
- "#魂これ"
- "Tamacolle"
- "tamacolle"
- "TamaColle"
- "地魂これくしょん"
- "河内くん"
- "河内君"
- "チヌちゃん"
- "伊賀くん"
- "伊賀君"
- "志摩くん"
- "尾張くん"
- "尾張君"
- "三河くん"
- "三河君"
- "相模くん"
- "相模君"
- "上総くん"
- "上総君"
- "上総さん"
- "下総くん"
- "下総君"
- "安房くん"
- "安房君"
- "常陸くん"
- "常陸君"
- "近江くん"
- "近江君"
- "信濃くん"
- "信濃君"
- "信濃先生"
- "若狭くん"
- "若狭君"
- "越後くん"
- "越後君"
- "丹波くん"
- "丹波君"
- "但馬くん"
- "但馬君"
- "因幡くん"
- "石見くん"
- "石見君"
- "播磨くん"
- "播磨君"
- "備中くん"
- "備中君"
- "備後くん"
- "備後君"
- "紀伊くん"
- "紀伊君"
- "讃岐くん"
- "讃岐君"
- "伊予くん"
- "伊予君"
- "土佐くん"
- "土佐君"
- "豊後くん"
- "豊後君"
- "豊後先生"
- "筑後くん"
- "筑後君"
- "大隅くん"
- "大隅君"
- "Tama Colle"
- "tama colle"

# denyList

> Deny list will exclude any results from a given user. You can provide the username or DID.
>
> - did:plc:1234
> - @spamspamspam.bsky.social

- @nowbreezing.ntw.app

# safeMode

> Safe mode limits the total number of API calls coming from Cloudflare.
>
> Set to `false` if you have higher limits via a paid Cloudflare plan.

true

# avatar

> This must link to an image (PNG or JPEG) in the same directory as this CONFIG.md. It doesn't have to be called `avatar.png`, but just be sure this CONFIG.md points to the correct file.

![](avatar.png)
