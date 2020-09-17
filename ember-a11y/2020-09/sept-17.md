# A11y Working Group Notes

- Where: Zoom [Link](https://linkedin.zoom.us/j/99486993411?pwd=TG96UFlKeGZxQldveW5kQlJRQmVYUT09)
- When: September 17, 2020 - https://meetingzone.app/utc/thursday/1800/
- Discord channel: #dev-ember-a11y

## Agenda
- [x] what day/time works for everyone?
- [x] update on active RFCs
- [x] ember-a11y org/repo maintenance plans
- [x] working on new linting rules

<!-- if you have an agenda item, submit a PR to add it here! -->

## Attendees (name/discord handle)

### Attendees

- [x] Melanie Sumner (Melanie#1618)
- [ ] Robert Jackson (rwjblue)
- [ ] Joseph Sumner	(Joseph#3648)
- [x] Rajasegar	(rajasegar)
- [ ] Abhilash (abhilashlr)
- [ ] Praskovia	(Praskovia#1618)
- [ ] Jamie White	(jgwhite#2348)
- [ ] Ava Gaiety Wroten (Gaiety) 
- [ ] Frédéric Soumare	(hakilebara)
- [ ] Emmanuel Patrick	(the-bionic)
- [ ] Eric Kelly
- [ ] Lennex Zinyando	(zinyando)
- [x] John Costanzo	(jrock2004#8583)
- [ ] Seema Shariat	(seemajune)
- [ ] Benjamin JEGARD	(@Benjamin JEGARD#7530) 
- [x] Steve Szczecina	(steveszc)
- [ ] Ricardo Mendes (locks)
- [x] Lenora Porter 
- [x] Sama Rao

<!-- want to join? Add yourself to this list! -->

## Discussion Notes

### Meeting Time

We're going to try Mondays to see if that encourages additional participation- seems like more folks in the group are available on Monday mornings. We are also going to regulary schedule a meeting that is better for the team members in India, so they can participate.

### RFCs

There are two group sponsored RFCs- we're going to try to move those through to FCP in the next week or two, since they have been quiet for long enough. If anyone has any comments on [id helper](https://github.com/emberjs/rfcs/pull/659) or [adding ember-page-title to the default blueprint](https://github.com/emberjs/rfcs/pull/645) then try to get them in soon.

### Ember A11y Org

* We're going to pin a message in the `dev-ember-a11y` channel on discord that keeps track of our addons and when they were last updated. 
* Not sure where to start? Check to see when a repo was last updated and if it uses dependabot or renovate. 
* Big-picture thinking is good too- file a tracking issue that outlines the vision for the addon, for transparency. See https://github.com/ember-a11y/ember-a11y-testing/issues/207 as a good example of this. 
* If you file a new issue, mark it with the `hacktoberfest` label, that way it can be done for the Digital Ocean event if folks want to participate in that.
* try to get a feel for the addons that are in the org- what purpose do they serve? next week, let's go through them and see if we want to still maintain them or if we should archive them. It's better for us to do fewer things but do them really well. 

### Ember Template Lint

* Mel has made an itemized list of ways that an app can fail A11y, so be on the look out for a lot more issues in `ember-template-lint` repo that will help us all create more accessible applications. 
* Heroku folks are going to submit a PR for a rule that will suggest use of the `scope` attributes on table headers (see https://github.com/ember-template-lint/ember-template-lint/issues/1494)

------------------------------------------------
Changes? Corrections? Please submit a PR. 
