# A11y Strike Team Notes

## Agenda
- [x] follow up on the TODOs
- [x] discuss Default Language Declaration ([Point #4 in RFC issue](https://github.com/emberjs/rfcs/issues/595))
- [x] update? id addon

## Attendees (name/discord handle)

- [x] Melanie Sumner (Melanie#1618)
- [ ] Robert Jackson (rwjblue)
- [ ] Jen Weber	(jenweber)
- [x] Amy Lam (amyrlam) 
- [x] Abhilash (abhilashlr)
- [x] Frédéric Soumare	(hakilebara)
- [x] Emmanuel Patrick	(the-bionic)
- [x] Eric Kelly
- [x] Lennex Zinyando	(zinyando)
- [ ] John Costanzo	(jrock2004#8583)
- [x] Rajasegar	(rajasegar)
- [ ] Praskovia	(Praskovia#1618)
- [ ] Seema Shariat	(seemajune)
- [x] Benjamin JEGARD	(@Benjamin JEGARD#7530) 
- [x] Steve Szczecina	(steveszc)
- [x] Jamie White	(jgwhite#2348)
- [x] Ava Gaiety Wroten (Gaiety) 
- [x] Joseph Sumner	(Joseph#3648)
- [x] Kelly Selden

## Discussion
- we can do better than just defaulting to lang="en" (discussion as to why or why not)
- MVP could be `--lang="en"` flag for ember-cli (requires RFC)
- additional flags have been avoided in ember-cli due to the number of permutations we'd need to test
- updating ember-cli tests would be useful if we were going to propose something, it's also an area where we could do some recruiting of experienced contributors
- also discoverability of flag options is kind of hard, how could we mitigate?
- - improve the docs
- - companion app/page that showed all options, allowed the user to select options, and then generated the command line to copy/paste into the terminal (fun side project opportunity)
- wizard workflow
- - `ember new my-app` would not trigger the wizard
- -- this would have a blank language attribute and linter rule that fails/gives a warning
- -- what happens if the lang attribute is there but blank? (Mel research please)
- -- if it's bad for the user we should automatically have a default
- -- build failures can be a bad DX
- -- on the flip side, companies who have stated a11y goals tend to break the build
- - `ember new` would trigger a wizard
- - in the wizard flow, we could have recommended defaults as the first options 
- - one of the language options could be "dynamic" or "intl" could include ember-intl?
- what's our question budget? what questions should be asked?
- - app name
- - language
- - no-welcome addon
- - yarn or npm
- vue does something like this
- - 2 things: yarn or npm, preset (default, manual- manual gives more options to go through)
- - vue sets `lang="en"` by default (even though it's very popular in China)
- developer system language? can we pull that as the default? add this to the RFC as an idea (consideration: what would this do for globally distributed developers?)

Overall, generally enthusiastic support from the group for the wizard/flow idea. A few folks were neutral.

### ID Addon work
- how is the id addon going? 
- https://github.com/KamiKillertO/ember-unique-id-helper
- still need to solve the template-only component issue

## Resulting TODOs
- [ ] work on RFC for `lang=xx` flag - Jamie, Joseph, & Ava
- [ ] work on prototype for wizard flow - Joseph 
- [ ] work on RFC for new ember app flow - Melanie
- [ ] work on ember-cli docs (this might be a stretch for this group, take to learning team)  

## Next Meeting Agenda
- website proposal
- follow up on the TODOs


------------------------------------------------
Changes? Corrections? Please submit a PR. 
