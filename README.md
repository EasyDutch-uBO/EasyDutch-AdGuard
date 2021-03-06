[EasyDutch-AdGuard](https://github.com/EasyDutch-uBO/EasyDutch-AdGuard):
[![Commit rate](https://img.shields.io/github/commit-activity/y/EasyDutch-uBO/EasyDutch-AdGuard?label=Commits&color=succes)](https://github.com/EasyDutch-uBO/EasyDutch-AdGuard/commits/)
[![Last commit](https://img.shields.io/github/last-commit/EasyDutch-uBO/EasyDutch-AdGuard?label=Last%20commit&color=informational)](https://github.com/EasyDutch-uBO/EasyDutch-AdGuard/commits/main)
[![Issues](https://img.shields.io/github/issues/EasyDutch-uBO/EasyDutch-AdGuard?label=Issues&color=red)](https://github.com/EasyDutch-uBO/EasyDutch-AdGuard/issues)
[![Issues](https://img.shields.io/github/issues-closed/EasyDutch-uBO/EasyDutch-AdGuard?color=green&label=Issues)](https://github.com/EasyDutch-uBO/EasyDutch-AdGuard/issues?q=is%3Aissue+is%3Aclosed)
[![License](https://img.shields.io/badge/License-GPLv3-blue.svg?label=License&color=lightgrey)](https://github.com/EasyDutch-uBO/EasyDutch-AdGuard/blob/main/LICENSE) <br>
(( [EasyList Dutch](https://github.com/easylist/easylistdutch/):
[![Commit rate](https://img.shields.io/github/commit-activity/y/easylist/easylistdutch?label=Commits&color=succes&style=plastic)](https://github.com/easylist/easylistdutch/commits/)
[![Last commit](https://img.shields.io/github/last-commit/easylist/easylistdutch?label=Last%20commit&color=informational&style=plastic)](https://github.com/easylist/easylistdutch/commits/master)
[![Issues](https://img.shields.io/github/issues/easylist/easylistdutch?label=Issues&color=red&style=plastic)](https://github.com/easylist/easylistdutch/issues)
[![Issues](https://img.shields.io/github/issues-closed/easylist/easylistdutch?color=green&label=Issues&style=plastic)](https://github.com/easylist/easylistdutch/issues?q=is%3Aissue+is%3Aclosed) ))

***
# EasyDutch
Adblock filters for Dutch websites made for [AdGuard](https://adguard.com/en/adguard-browser-extension/overview.html)

| Contents |
| --- |
| [EasyDutch-AdGuard](#easydutch-adguard) |
| [Contributing](#contributing) |
| [View and Subscribe](#view-and-subscribe-to-easydutch) |
| [Support](#support) |
-----
## [EasyDutch-AdGuard](https://github.com/EasyDutch-uBO/EasyDutch-AdGuard)
The updated version of EasyList Dutch special for AdGuard. 

This filterlist has been made as nice supplement to [EasyDutch](https://github.com/EasyDutch-uBO/EasyDutch-AdGuard) 
If you see ads on dutch websites please [report](https://github.com/EasyDutch-uBO/EasyDutch/issues/new/choose) it to me or sent me an email to easydutch.adblock@gmail.com <br>

## [Contributing](https://github.com/EasyDutch-uBO/EasyDutch-AdGuard/blob/main/CONTRIBUTING.md)
<details>
<summary>Contributing</summary>

> Important note: </br>
> I, @BPower0036 owner of EasyDutch, prefer simplicity over complexity. So instead of `123geldzaken.nl##[class*="widget_sponsor"]` use 
`123geldzaken.nl##.widget_sponsor` and `123geldzaken.nl##.widget_sponsorlinks`. And instead of `arenalokaal.nl##[advobject]:upward(.bg-gray-100):has-text(/Uit de 
krant/i)` just use `arenalokaal.nl##[advobject]:upward(.bg-gray-100)`
>
> ##### Ordering of filters
> 
> New filters must be added on the top of each list.
> 
> The reason is to provide an easy way to check whether a filter is still relevant. The filters at the end of the file will be the oldest filters, and also the most likely to maybe be obsolete.
> 
> Old filters which are confirmed to still be required must be moved to the top of the list.
> 
> ##### Issue number association
> 
> **All** added filters must be associated with a formal issue number or date, example:
> 
>     ! https://github.com/EasyDutch-uBO/EasyDutch/issues/3
>     ||data.inertanceretinallaurel.com^
>     ! 2021-04-27
>     ||androidplanet.nl,iphoned.nl##.dynamic-content-native
> 
> This way this documents why a filter was added, and how to verify whether an old filter is still needed. The comment line preceding the filter(s) to solve a specific issue should be only a URL to the issue. The issue itself can contains all the details about how the issue was solved, and why it was solved this way, etc.
> 
> ##### Commit message
> 
> - Keep it simple, use `A:` for adding a site, `C:` for changing or updating rules, `R:` for removing, and `M:` for moving to other files. 
> - Put here after the site url `spele.nl` (no `https://www.`) 
> - Put after this the issue number. </br>
> Example: `A: spele.nl fix #3` or `C: nu.nl`. The issue itself will contains all the details.
> 
> ##### Hide General
> 
> You may only make General Hiding rules, if it applies to tree or more websites
> 
> *******
> #### What you might do or not do as a contributor
> 
> As a contributor it is **forbidden** to change the following files:
> - `.github` folder 
> - `README.md`
> - `CONTRIBUTING.md`
> - `CODE_OF_CONDUCT.md`
> - `LICENSE`
> 
> The rest you may change.
> 
> Breaching this rule will result in a warning and if not listening, being banned as contributor!

</details>

***
## View and Subscribe to EasyDutch
| _**View**_ | GitLab | Combinatronics | Statically | JSdelivr |
| ---------- | ------ | :------------: | ---------- | -------- |
| 1. [EasyDutch](https://raw.githubusercontent.com/EasyDutch-uBO/EasyDutch-AdGuard/main/EasyDutch-AdGuard.txt) | [Mirror 1](https://gitlab.com/BPower0036/EasyDutch-AdGuard/-/raw/main/EasyDutch-AdGuard.txt) | [Mirror 2](https://combinatronics.io/EasyDutch-uBO/EasyDutch-AdGuard/main/EasyDutch-AdGuard.txt) | [Mirror 3](https://cdn.statically.io/gh/EasyDutch-uBO/EasyDutch-AdGuard/main/EasyDutch-AdGuard.txt) / [Mirror 3.1](https://cdn.statically.io/gl/BPower0036/EasyDutch-AdGuard/raw/main/EasyDutch-AdGuard.txt) | [Mirror 4](https://cdn.jsdelivr.net/gh/EasyDutch-uBO/EasyDutch-AdGuard@main/EasyDutch-AdGuard.txt) |

| _**Subscribe**_ | GitLab | Combinatronics | Statically | JSdelivr |
| --------------- | ------ | :------------: | ---------- | -------- |
| 1. [EasyDutch](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/EasyDutch-uBO/EasyDutch-AdGuard/main/EasyDutch-AdGuard.txt&title=EasyDutch-AdGuard) | [Mirror 1](https://subscribe.adblockplus.org/?location=https://gitlab.com/BPower0036/EasyDutch/-/raw/main/EasyDutch-AdGuard.txt&title=EasyDutch-AdGuard) | [Mirror 2](https://subscribe.adblockplus.org/?location=https://combinatronics.io/EasyDutch-uBO/EasyDutch-AdGuard/main/EasyDutch-AdGuard.txt&title=EasyDutch-AdGuard) | [Mirror 3](https://subscribe.adblockplus.org/?location=https://cdn.statically.io/gh/EasyDutch-uBO/EasyDutch-AdGuard/main/EasyDutch-AdGuard.txt&title=EasyDutch-AdGuard) / [Mirror 3.1](https://subscribe.adblockplus.org/?location=https://cdn.statically.io/gl/BPower0036/EasyDutc-AdGuard/raw/main/EasyDutch-AdGuard.txt&title=EasyDutch-AdGuard) | [Mirror 4](https://subscribe.adblockplus.org/?location=https://cdn.jsdelivr.net/gh/EasyDutch-uBO/EasyDutch-AdGuard@main/EasyDutch-AdGuard.txt&title=EasyDutch-AdGuard) |

## *Support*
If you want to buy me a cup of coffee or want to support me, you can donate via [PayPal](https://www.paypal.com/donate/?hosted_button_id=NRARDMBBMV3LC)

###### Contributor : [JohnyP36](https://github.com/JohnyP36)
