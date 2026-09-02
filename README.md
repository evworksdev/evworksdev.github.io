# evworksdev.github.io

The developer website for **EVWORKS** apps. Two files do the work:

| File | Why it's here |
|---|---|
| `index.html` | Landing page for **Proteus**, the Android protein tracker. The canonical link for press, forums and the Play listing. |
| `app-ads.txt` | IAB Tech Lab authorised-sellers file. AdMob crawls `https://evworksdev.github.io/app-ads.txt` — the **domain root**, which is the whole reason this is a user-site repo. |

It is deliberately **not** `github.com/evworksdev`: that is a profile page on a domain
we do not own, so AdMob would fetch `https://github.com/app-ads.txt` and never verify.

> **These files are copies.** The canonical sources live in `docs/site/` in the
> Proteus repository — edit them there and copy across. Editing here means the next
> copy silently reverts you. One deliberate difference: the canonical `app-ads.txt`
> carries deployment notes that have no business on a public URL an ad crawler
> fetches. Only the **record line** is authoritative, and it is identical in both.

Privacy policy: <https://mynameiseyal.github.io/privacy/proteus/> — still served from
its own project repo. That URL is quoted in the merchant profile, the live Play
listing and the AdMob consent message, so moving it is a sequenced job of its own.

Contact: evworks.dev@gmail.com
