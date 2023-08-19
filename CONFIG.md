
# recordName

> This is the feed's ID which can be letters, numbers, or dashes. Spaces are not allowed. Maximum length is 15 characters.

My-List

# displayName

> This is the title of the custom feed. Maximum length is 24 characters.

ようこそ

# description

> This is the description of the feed.

知っていると便利そうなことをまとめました。

# searchTerms

> There are three types of search terms:
>
> - Keywords: Test these in [https://bsky.app/search](https://bsky.app/search). `AND` is implicit, so `cat dog` on one line will require both `cat` and `dog`. You can use quotes as well `"hot dog"`.
> - Users: links such as `https://bsky.app/profile/why.bsky.team` will pull in the user's posts. To include replies and reposts, you can add the following flags: `https://bsky.app/profile/why.bsky.team +replies +reposts`.
> - Pinned posts: links such as `https://bsky.app/profile/saddymayo.bsky.social/post/3jxju2wwap22e` will pin at the top of the feed. One link per line, please.

- https://bsky.app/profile/ffi.bsky.social/post/3k5bnxtbhow2v
- https://bsky.app/profile/littlehermit.bsky.social/post/3k3ltsc6h4p2x
- https://bsky.app/profile/zatsumu.bsky.social/post/3k4ijrkivn62d
- https://bsky.app/profile/yukotan.bsky.social/post/3jzlwevo3cz2m
- https://bsky.app/profile/matope.bsky.social/post/3k3fxnfjd7n2z
- https://bsky.app/profile/ffi.bsky.social/post/3k4ek3htv3x25
- https://bsky.app/profile/ffi.bsky.social/post/3k3z5yyx4fu2y
- https://bsky.app/profile/showya.bsky.social/post/3k5anrgr7qy2z

# safeMode

> Safe mode limits the total number of API calls coming from Cloudflare.
>
> Set to `false` if you have higher limits via a paid Cloudflare plan.

true

# avatar

> This must link to an image (PNG or JPEG) in the same directory as this CONFIG.md. It doesn't have to be called `avatar.png`, but just be sure this CONFIG.md points to the correct file.

![](avatar.png)
