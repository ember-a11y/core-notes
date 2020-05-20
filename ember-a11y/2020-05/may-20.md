# A11y Strike Team Notes

- Where: Zoom Link: https://linkedin.zoom.us/j/954393219
- When: May 20, 2020 - https://meetingzone.app/utc/wednesday/1600/

## Agenda
- [x] GAAD blog post & outreach
- [x] update on `--lang` flag work
- [x] new app flow discussion
- [x] ember-template-lint

## Attendees (name/discord handle)

### Strike Team

- [x] Melanie Sumner (Melanie#1618)
- [ ] Robert Jackson (rwjblue)
- [ ] Jen Weber	(jenweber)
- [ ] Amy Lam (amyrlam) 
- [x] Jamie White	(jgwhite#2348)
- [x] Ava Gaiety Wroten (Gaiety) 
- [x] Joseph Sumner	(Joseph#3648)
- [x] Rajasegar	(rajasegar)
- [x] Abhilash (abhilashlr)
- [x] Frédéric Soumare	(hakilebara)
- [ ] Emmanuel Patrick	(the-bionic)
- [ ] Eric Kelly
- [ ] Lennex Zinyando	(zinyando)
- [ ] John Costanzo	(jrock2004#8583)
- [ ] Praskovia	(Praskovia#1618)
- [ ] Seema Shariat	(seemajune)
- [x] Benjamin JEGARD	(@Benjamin JEGARD#7530) 
- [x] Steve Szczecina	(steveszc)

### Guests
- Locks
- Lenora 

## Discussion Notes

### GAAD (May 21)
- blog post will go up as a PR 
- Companies who have done A11y work in May: Crowdstrike, LinkedIn, 
- PR review for edits: Ben, Raja, abhilashlr
- Tweets from the EmberJS Twitter feed

### update on `--lang` flag
- Code Status: https://github.com/josephdsumner/ember-cli/compare/master...josephdsumner:ember-new-lang-util#files_bucket
- RFC draft will be ready next week(ish)
- will add disallowed list for better clarity for developers
- will it have a message when it fails due to incorrect value? yes, working on it

### wizard question (discussion)
- how many questions do we want to ask
- how many questions do we think devs will tolerate
- should the questions branch based on app vs addon?

questions: 
- app or addon (default is app)
- app name? 
- app language (for lang attribute)? (default `en`)
- yarn or npm? (default `npm`)

- welcome addon (leave as flag?)
- typescript? (yes/no, default is `no`)

- addons: which CI do you want (default is none, & we would set different files for them based on their CI-as-a-service preference. Options Travis, GitHub Actions, Circle CI, Appveyor, none) 
- [ ] action item, Joseph - look at the survey and see what was the most popular this year
- addons: which versions of Ember do you want to support

- saving as preset (need to think about how we could do this) (abhilashlr will work on figuring it out)
- locks suggests we should make sure we don't duplicate effort for what Kelly Selden has recently figured out re:saving preferences for blueprints 
- locks is available to talk shop about the wizard technical details if anyone is interested
- recommend chatting in #dev-ember-cli channel on Discord 

### ember-template-lint

- overview of the addon, how to use it, things to consider when you're getting your team to use it
- contributing: issues in repo should be good, let Mel know if you need more clarity
- contributing opportunity: check guides and api docs to see if there are code samples that violate the rules in ember-template-lint - if you're up for more tricky work, figure out how to integrate ember-template-lint into guides/api docs
- if you want to contribute, please do! check out astexplorer.net for more.

## Next Meeting Agenda
- review progress on the website (Frederic)
- context-id-helper, new version, still working on template-only Glimmer components (Ben)


------------------------------------------------
Changes? Corrections? Please submit a PR. 
