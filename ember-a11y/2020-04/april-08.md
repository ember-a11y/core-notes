# A11y Strike Team Notes

## Agenda
- https://github.com/emberjs/rfcs/issues/595
- discussion for this week: Page Titles

## Attendees (name/discord handle)

- [x] Melanie Sumner (Melanie#1618)
- [x] Robert Jackson	(rwjblue)
- [x] Jen Weber	(jenweber)
- [x] Abhilash (abhilashlr)
- [x] Frédéric Soumare	(hakilebara)
- [x] Emmanuel Patrick	(the-bionic)
- [x] Eric Kelly (heroiceric)
- [x] Lennex Zinyando (zinyando)
- [ ] John Costanzo	(jrock2004#8583)
- [ ] Rajasegar	(rajasegar)
- [x] Praskovia	(Praskovia#1618)
- [ ] Seema Shariat	(seemajune)
- [x] Benjamin JEGARD	(@Benjamin JEGARD#7530) 
- [x] Steve Szczecina	(steveszc)
- [x] Jamie White	(jgwhite#2348)
- [x] Ava Gaiety Wroten (Gaiety) 
- [x] Joseph Sumner	(Joseph#3648)

## Discussion

### Goal
New Ember Apps should provide default support for page titles.

### Solution Constraints

- must be fastboot compatible 
- generator should set up a page title place for a new route
- should default to a template-based solution, but have room for a different approach

## Resulting TODOs

- [ ] ember-cli-document-title should be refactored to use ember-cli-head, so it matches ember-page-title
- [ ] RFC to add ember-title (based on ember-cli-head) to default blueprint
- [ ] Add information to guides 
- [ ] Add something that at least derives the title from route name
- [ ] Test helper to assert that the page title is there (sort of like how you can assert on currentUrl)

## Next Meeting Agenda

We will come back to labels and check to see where we are with that.
