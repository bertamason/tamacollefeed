
# recordName

> This is the feed's ID which can be letters, numbers, or dashes. Spaces are not allowed. Maximum length is 15 characters.

tamacolle-kw

# displayName

> This is the title of the custom feed. Maximum length is 24 characters.

HT VER2

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
- "Tama Colle"
- "TamaColle"
- "Kazusa"
- "大和くん"
- "河内くん"
- "和泉くん"
- "伊賀くん"
- "志摩くん"
- "尾張くん"
- "三河くん"
- "甲斐くん"
- "相模くん"
- "武蔵くん"
- "上総くん"
- "下総くん"
- "安房くん"
- "常陸くん"
- "近江くん"
- "信濃くん"
- "若狭くん"
- "加賀くん"
- "越後くん"
- "丹波くん"
- "但馬くん"
- "因幡くん"
- "石見くん"
- "隠岐くん"
- "播磨くん"
- "備中くん"
- "備後くん"
- "紀伊くん"
- "讃岐くん"
- "伊予くん"
- "土佐くん"
- "豊後くん"
- "筑後くん"
- "肥前くん"
- "大隅くん"
- "大和君"
- "河内君"
- "和泉君"
- "伊賀君"
- "志摩君"
- "尾張君"
- "三河君"
- "甲斐君"
- "相模君"
- "武蔵君"
- "上総君"
- "下総君"
- "安房君"
- "常陸君"
- "近江君"
- "信濃君"
- "若狭君"
- "加賀君"
- "越後君"
- "丹波君"
- "但馬君"
- "因幡君"
- "石見君"
- "隠岐君"
- "播磨君"
- "備中君"
- "備後君"
- "紀伊君"
- "讃岐君"
- "伊予君"
- "土佐君"
- "豊後君"
- "筑後君"
- "肥前君"
- "大隅君"
- "大和さん"
- "河内さん"
- "和泉さん"
- "伊賀さん"
- "志摩さん"
- "尾張さん"
- "三河さん"
- "甲斐さん"
- "相模さん"
- "武蔵さん"
- "上総さん"
- "下総さん"
- "安房さん"
- "常陸さん"
- "近江さん"
- "信濃さん"
- "若狭さん"
- "加賀さん"
- "越後さん"
- "丹波さん"
- "但馬さん"
- "因幡さん"
- "石見さん"
- "隠岐さん"
- "播磨さん"
- "備中さん"
- "備後さん"
- "紀伊さん"
- "讃岐さん"
- "伊予さん"
- "土佐さん"
- "豊後さん"
- "筑後さん"
- "肥前さん"
- "大隅さん"
- "信濃先生"
- "豊後先生"

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
