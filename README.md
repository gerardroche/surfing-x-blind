# Surfing X Blind

uBlock Origin filters to remove things like like counts, view counts, etc. when browsing X.

- Hides like counts
- Hides retweet counts
- Hides reply counts
- Hides view counts
- Hides post time
- Hides following count
- Hides follower count
- Hides profile pop-up on hover
- Hides sidebar trending panels

Toggle the filters via the eye icon in the uBlock Origin UI.

## X post before and after

![X post after screenshot](x-post.gif)

![X post before screenshot](x-post.jpg)

## Setup

Requires uBlock Origin or other Adblock Plus compatible blocker like [Brave Browser](https://brave.com/).

Navigate to your [uBlock Origin](https://github.com/gorhill/uBlock) **Filter lists**, scroll to **Import...**, and add the filter URL below, and click **Apply changes**.

```
https://raw.githubusercontent.com/gerardroche/surfing-x-blind/refs/heads/master/surfing-x-blind.txt
```

Alternatively, manually copy the filters directly into your custom filters via the "My Filters" tab in uBlock Origin settings.
