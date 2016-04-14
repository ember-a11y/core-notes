# ember-a11y Meeting Notes - 2016-04-13

## Attendees

- Nathan Hammond
- Robert DeLuca
- Melanie Sumner
- Ben Holmes
- Suz Hinton

## Actions

- [ ] @jgwhite - Write up a blog post on our focus.
- [ ] @nathanhammond - Invite Suz to the TurnItIn meeting.
- [ ] @ember-a11y/core - Review Rob's WGE proposal.
- [ ] @nathanhammond - Reach out to Apple people.
- [ ] @nathanhammond - Components demo base application.
- [ ] @melsumner, @binhums - Help build demo page.
- [ ] @robdel12 - Reach out to @miguelcobain about ember-power-select.

## Discussion Notes

### Meeting Format, Planning

- How should this meeting run?
  - "Get stuff done" to start. Heavily moderated.
  - Open conversation to follow which will lead to additional conversations.

### Team Focus

- End goal: get all of this into "core."
  - Subdivide into bite-sized tasks so that we're not trying to boil the ocean.
  - Avoid additions into actual Ember, but possibly get things added to the default blueprint.
  - Design our efforts so that at some future point it's "this will of course be part of core."
  - The "SDK for the Web" should be accessible by default.
  - Paying attention to RFCs and new/existing features in Ember.js to ensure that we address a11y.
- Outreach?
  - As this matures this could expand interest in Ember to more restricted spaces which have a11y requirements.
  - "Good for New Contributors" comes with a full "how to do this" guide. Be as beginner friendly as feasibly possible.
  - Work with addon community (e.g. ember-power-select) to make them accessible.
  - Avoid accidentally owning the entire community's accessibility, be a resource, not the team responsible.
- Code?
  - Review built-in Ember features for accessibility.
    - `{{link-to}}`
    - `{{input}}`
    - `{{outlet}}`
    - etc.
- Teaching/Speaking?
  - Write strong documentation in CONTRIBUTING.md.
  - Spread the good news.

### Consolidation of Efforts

- GitHub organization!
  - We are consolidating all of the individual projects in this space into one organization.
  - Allows for community ownership and maintenance.
  - a11y-announcer, ember-a11y, ember-a11y-testing (née ember-aXe), ember-component-focus
  - Maintaining our own fork of core-notes for these notes.

### liquid-fire

- Has a lot of weird gotchas like old and new content coexisting.
- Working with the TurnItIn team on morning of 4/20 to teach them how to contribute..

### Talks

- Rob to submit proposal for Wicked Good Ember. Basic premise is to move a11y requirements to top of the list.
- Suz speaking about SPA accessibility at Dinosaur.js in Denver.

### Apple VoiceOver

- Apple team wants to build a page with all Ember native ember widgets that they can test VoiceOver against.
- All core pieces should be present.
- Possibly include popular addons. (Review top 100 on Ember Observer.)
