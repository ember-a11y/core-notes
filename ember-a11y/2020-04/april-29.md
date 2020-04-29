# A11y Strike Team Notes

## Agenda

Mostly status updates for existing work (current status, next steps, any blockers)-

- [ ] update: website proposal (Frédéric)
- [x] update: `ember-title` [addon](https://github.com/rwjblue/ember-title)
- [x] update: RFC for `lang=xx` flag (Jamie, Ava, Joseph)
- [x] update: addon for `id` (Steve, Eric, Emmanuel, Benjamin)
- [x] help wanted: [A11y-focused rule requests in ember-template-lint](https://github.com/ember-template-lint/ember-template-lint/issues/created_by/MelSumner)
- [x] discussion: GAAD

## Attendees (name/discord handle)

- [x] Melanie Sumner (Melanie#1618)
- [x] Robert Jackson (rwjblue)
- [ ] Jen Weber	(jenweber)
- [ ] Amy Lam (amyrlam) 
- [ ] Abhilash (abhilashlr)
- [ ] Frédéric Soumare	(hakilebara)
- [ ] Emmanuel Patrick	(the-bionic)
- [ ] Eric Kelly
- [x] Lennex Zinyando	(zinyando)
- [ ] John Costanzo	(jrock2004#8583)
- [x] Rajasegar	(rajasegar)
- [x] Praskovia	(Praskovia#1618)
- [ ] Seema Shariat	(seemajune)
- [x] Benjamin JEGARD	(@Benjamin JEGARD#7530) 
- [ ] Steve Szczecina	(steveszc)
- [x] Jamie White	(jgwhite#2348)
- [x] Ava Gaiety Wroten (Gaiety) 
- [x] Joseph Sumner	(Joseph#3648)

(add yourself here if you attend)

## Discussion Notes

### ember-title
- "readme driven development"
- there are some tricky bits, outlined briefly in the README
- some of the next steps are identified in the repo issues
- MVP should really address the issue since other addons exist that allow you to do either solution separately
- if we need to get this into a timeline, a template focused solution seems more aligned with Octane, so we could recommend ember-page-title as the default (as a punt)
- we could start authoring the RFC, starting with ember-page-title and then swapping ember-title as the work progresses

### RFC for lang 
- first meeting was today, will meet a few times a week
- will work on RFC 
- Joseph working on prototype implementation
- no blockers
- yarn flag RFC is perhaps a close-ish RFC to look at for comparisons. Def include motivations and outline workflow

### ID helper
- https://github.com/KamiKillertO/ember-unique-id-helper - will try to publish this week
- doesn't work for template-only components
- there's [another addon](https://emberobserver.com/addons/@ember-lux/id-helper) that we can also evaluate
- we need a way to pass the context to the helper
- we could use `let` to provide context (template only components do not have a `this`) 

### Global Accessibility Awareness Day
- Third Thursday each May
- MVP would be a blog post that outlines the benefits of Ember for a11y purposes, and highlight additional improvements coming through the strike team
- include stats "we are the most accessible framework" and talk about why
- could we do something "event-like" and have something like office hours or virtual reviews?
- Mel to check with Rob D to ask about the office hours app 
- blog series for each day in May until the day of- rajasegarc will compile a list and share it in discord channel so we can decide in the next 24-48 hrs
- a few years back we had a drive to contribute a11y fixes to addons - maybe we could try a drive for companies that use Ember could do some fixes to their apps and we could highlight the companies that fixed bugs to address a11y issues
- MVP could be announcement about the idea, if folks want to participate they could PR to a blog draft or email in. Any fix in May would count

## Next Meeting Agenda
- website update
- we'll figure it out and post the agenda to the channel. 


------------------------------------------------
Changes? Corrections? Please submit a PR. 
