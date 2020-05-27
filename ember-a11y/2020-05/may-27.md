# A11y Strike Team Notes

- Where: Zoom Link: https://linkedin.zoom.us/j/954393219
- When: May 20, 2020 - https://meetingzone.app/utc/wednesday/1600/

## Agenda
- [x] update on `--lang` flag work (Joseph)
- [ ] review progress on the website (Frederic) (moved to next week)
- [ ] context-id-helper, new version, still working on template-only Glimmer components (Ben) (moved to next week)

## Attendees (name/discord handle)

### Strike Team

- [x] Melanie Sumner (Melanie#1618)
- [x] Robert Jackson (rwjblue)
- [x] Joseph Sumner	(Joseph#3648)
- [x] Rajasegar	(rajasegar)
- [x] Abhilash (abhilashlr)
- [x] Praskovia	(Praskovia#1618)
- [ ] Amy Lam (amyrlam) 
- [ ] Jamie White	(jgwhite#2348)
- [ ] Ava Gaiety Wroten (Gaiety) 
- [ ] Frédéric Soumare	(hakilebara)
- [ ] Emmanuel Patrick	(the-bionic)
- [ ] Eric Kelly
- [ ] Lennex Zinyando	(zinyando)
- [ ] John Costanzo	(jrock2004#8583)
- [ ] Seema Shariat	(seemajune)
- [ ] Benjamin JEGARD	(@Benjamin JEGARD#7530) 
- [ ] Steve Szczecina	(steveszc)

### Guests
- [x] Ricardo Mendes (locks)

## Discussion Notes
Reviewed [draft RFC](https://github.com/sharpshark28/rfcs/blob/ember-new-lang/text/0000-ember-new-lang.md) and [candidate implementation](https://github.com/josephdsumner/ember-cli/compare/master...ember-new-lang-base) related to proposed change.

Resulting todos:
Candidate Implementation:
- [ ] change agnostic default value from empty string to undefined
- [ ] add tests - index-test.html
- [ ] fixture tests; entire file
- [ ] add ts js etc cases, check misuse before validation
- [ ] tidy up implementation for HTML flag

RFC Draft:
- [ ] include references for global digital a11y requirements
- [x] include super rentals update in "how we teach this" 
- [ ] add examples of what happens if it's done incorrectly (extract high-level prose from RFC issue details)
- [x] move `lang` up to design since it's not an unresolved question but rather a design choice
- [ ] improve "how we teach this" with content for the CLI guides (basically should be an MVP for a CLI guides PR)
- [ ] add the technical details from candidate implementation along with prose, into the detailed design section (don't just link to it)

After the RFC is submitted, a draft PR can be submitted to ember-cli for further review.


Moved agenda items to next week for folks who were scheduled to present but unable to make it today.

## Next Meeting Agenda
- [ ] review progress on the website (Frederic)
- [ ] context-id-helper, new version, still working on template-only Glimmer components (Ben)


------------------------------------------------
Changes? Corrections? Please submit a PR. 
