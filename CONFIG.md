
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
- "地魂これくしょん"
- "河内くん"
- "河内君"
- "河内さん"
- "チヌちゃん"
- "伊賀くん"
- "伊賀君"
- "伊賀さん"
- "志摩くん"
- "尾張くん"
- "尾張君"
- "尾張さん"
- "三河くん"
- "三河君"
- "三河さん"
- "相模くん"
- "相模君"
- "相模さん"
- "上総くん"
- "上総君"
- "上総さん"
- "上総さん"
- "下総くん"
- "下総君"
- "下総さん"
- "安房くん"
- "安房君"
- "安房さん"
- "常陸くん"
- "常陸君"
- "常陸さん"
- "近江くん"
- "近江君"
- "近江さん"
- "信濃くん"
- "信濃君"
- "信濃さん"
- "信濃先生"
- "若狭くん"
- "若狭君"
- "若狭さん"
- "越後くん"
- "越後君"
- "越後さん"
- "丹波くん"
- "丹波君"
- "丹波さん"
- "但馬くん"
- "但馬君"
- "但馬さん"
- "因幡くん"
- "石見くん"
- "石見君"
- "石見さん"
- "播磨くん"
- "播磨君"
- "播磨さん"
- "備中くん"
- "備中君"
- "備中さん"
- "備後くん"
- "備後君"
- "備後さん"
- "紀伊くん"
- "紀伊君"
- "紀伊さん"
- "讃岐くん"
- "讃岐君"
- "讃岐さん"
- "伊予くん"
- "伊予君"
- "伊予さん"
- "土佐くん"
- "土佐君"
- "土佐さん"
- "豊後くん"
- "豊後君"
- "豊後さん"
- "豊後先生"
- "筑後くん"
- "筑後君"
- "筑後さん"
- "大隅くん"
- "大隅君"
- "大隅さん"
- "Tama Colle"
- "TamaColle"
- "Tamacolle"
- "tamacolle"
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
