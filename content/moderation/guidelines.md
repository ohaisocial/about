+++
title = "Moderation guidelines"
date = "2019-02-28"
author = "Hugo Authors"
+++

These guidelines are mostly intended for moderators of ohai.social to aid them in their decisions while handling reports, and to ensure similar reports are handled with consistency.

They are not part of the rules as such, but hopefully help understand the way we enforce them.

Please note that this is a living document that gets updated from time to time as consensus on more situations and rules forms.

## Rules

This list gives a more detailed overview on what types of content fall under which rules, and on what actions to take when they are broken.

### We do not tolerate discriminatory behavior and content promoting or advocating the oppression of members of marginalized groups.

### We do not tolerate threatening behavior, stalking, doxxing, or harassment (including brigading, dogpiling, or any other form of contact with a user who has stated that they do not wish to be contacted).

### We do not tolerate violent nationalist propaganda, Nazi symbolism or promoting the ideology of National Socialism.

This rule could in theory be generalized (and is technically also covered by the 'No content illegal in Germany' rule), but I think it is a good idea to explicitly spell it out.

### We do not tolerate conspiracy narratives or other reactionary myths supporting or leading to the above-mentioned (and/or similar) behavior.

Todo: Clarification what this encompasses (Afaik rule was originally added on chaos.social in response to Covid conspiracy stuff)

### All explicit (NSFW) content must be marked as sensitive and have a content warning. Explicit content must not be used in user avatars or header images.


Maybe change rule to more explicitly ban the 'low-effort porn dump' type accounts that keep showing up, but need to come up with wording and general policy.

**Action:** NSFW posts without both a content warning and media marked as sensitive should be deleted. Posts with images that have content warning, but are not marked as 'sensitive content' usually get marked sensitive using report UI. Might be worth considering deleting these too, because (afaik) users don't get notified about this and might post without marker again, whereas deleting provides feedback via email.

Todo: Clearer definition of what exactly counts as sexual content.

### Content that is illegal in Germany will be deleted and may lead to immediate account suspension.

Holocaust denial / Incitement to hatred
: [Relevant law](https://www.gesetze-im-internet.de/englisch_stgb/englisch_stgb.html#p1368)
: **Action:** Users posting this type of content should be suspended immediately.

Dissemination of propaganda material of unconstitutional and terrorist organisations / Use of symbols of unconstitutional and terrorist organisations
: [Relevant law](https://www.gesetze-im-internet.de/englisch_stgb/englisch_stgb.html#p0922). Also see [list on Wikipedia with illustrations](https://en.wikipedia.org/wiki/Strafgesetzbuch_section_86a#Symbols_affected).
: Notable examples: [Swastika](https://en.wikipedia.org/wiki/File:NSDAP_Hakenkreuz.svg) (unless used in religious context of Hinduism/Bhuddism), [ISIS flag](https://en.wikipedia.org/wiki/File:AQMI_Flag_asymmetric.svg), [stylized Celtic cross](https://en.wikipedia.org/wiki/File:Celtic_cross.svg), [KKK solar cross](https://en.wikipedia.org/wiki/File:Crossed_circle.svg), russian military ['Z' symbol](https://en.wikipedia.org/wiki/File:2022_Russian_Invasion_vehicle_marking_Z.svg). These can be permissible when used in a clearly disparaging way, for example when crossed out. Can also be acceptable when used in art or for journalistic/documentary/illustrative purposes.
: **Action:** Users posting this type of content should be suspended immediately.

Unauthorized use of copyrighted content
: Emphasis on *unauthorized*. Also, some uses of copyrighted content are acceptable even without permission by the copyright holder(s) (Todo: List examples)
: **Action:** On first offense, delete the posts in question. If it happens again, either send a warning to the user asking them to refrain from posting copyrighted content, or suspend directly, depending on situation.
: Accounts that were clearly only created to post copyrighted material should be suspended immediately.

## General
Consider wider patterns of harassment outside of the context of an individiual post
: Todo: user a harasses user b for months, user b lashes out against user a once, that posts gets reported and user b gets suspended <- These types of situations should be avoided 

Provide feedback where appropriate
: Mastodon doesn't provide any feedback to a reporter once their report has been handled. This means that sometimes reporting things on Mastodon can feel a bit like shouting into a void.
: While it's not feasible to send a message to every reporter once their report is handled (And completely impossible for reports from other servers), there may be instances where it is a good idea to let a user know using a quick direct message that their report has been handled.

## Specific situations

User intentionally breaks rules a second time
: Users that got a post deleted, and then soon after create a new post clearly _intentionally_ breaking the _same_ rule should be suspended. 'Clearly' here means situations where the user directly comments on their previously deleted post while breaking the rules again, or is otherwise obviously aware that their previous post got deleted for breaking rules.

Rule breaks in response to harassment
: Sometimes, situations come up where one user harasses another user in a post, and that user then responds to this with a post that may also break the rules (Using personal insults or something).
: While technically both users violated the rules, they should not be treated equally as the intent was clearly different. We do not want to just "both sides" these types of incidents. Obviously specific handling depends on the exact types of posts, a 

## Trending content

The content shown in the 'Explore' tab and on the public front page of the instance needs to be manually whitelisted before being shown.

### Hashtags
We allow all hashtags to trend as long they're not used to brigade individual people, are part of some organized harrasment campaign or otherwise break rules.

### Links
No links that have content that would break the rules of ohai.social.

Trending links are shown without the post(s) they were linked in, so sometimes it doesn't make sense to allow them even if they don't break rules. For example, at one point there was a link to a Google Docs Form that didn't really make sense without the context of the original post.

Websites of large, trustworthy publications or organizations (BBC, ACLU/EFF blog, stuff like that) can be whitelisted entirey ('Allow publisher') to allow future links to show up automatically.

Sometimes, links to Mastodon posts pop up in the trending links list. Generally we try not to whitelist those as they will probably show up in the 'Popular posts' tab anyway, but for some it can make sense to allow them.

### Posts
Like with hashtags, generally all posts are allowed to trend as long as they're not upsetting news/content without a Content Warning or otherwise break rules.

It's also possible to whitelist entire accounts so their future posts get automatically allowed. This should mostly be reserved to 'group'/organization accounts like mastodon@mastodon.online or feditips@mstdn.social.  Individual persons should be whitelisted sparingly, but it can make sense with some larger accounts that frequently trend and are generally unproblematic.

## Instance silencing/deferation

Todo: A general policy of when to suspend vs. limit instances. Currently we mostly use full suspensions, but in some cases only limiting the instance might suffice?

Grounds for direct suspension/defederation:
* Instances that clearly only exist to facilitate harassment/trolling.
* Instances that self-describe as 'free speech zone' or 'without moderation' or something to that effect (Todo: Limiting those might suffice? But we probably don't want users who would follow the content from these instances either).
* Instances that permit content that is illegal under German law (see above).
* Twitter mirrors (Mostly BirdsiteLive instances). They're not actively harmful, but constantly get confused with fake accounts by new users, use up comparatively much database space and generally add relatively little value. That said if a user sets up a non-public twitter mirror only for their own use, that might be okay.

Reasons to limit instances:
* Up to now we have only used the limit functionality for servers that are excessively spammy without being particularly harmful otherwise (e.g. brands.town) or that have a lot of untagged NSFW content
* There have been some arguments made that limiting should be the default and suspension should be reserved for instances containing illegal/malicious content. But I don't know how I feel about that.
