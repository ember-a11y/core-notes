# ember-a11y Meeting Notes - 2016-05-11

## Attendees

- Nathan Hammond
- Ben Holmes
- Melanie Sumner
- Suz Hinton
- Robert DeLuca
- David Peter
- Jamie White
- Amanda - CART

## Actions

- [ ] GAAD
  - [ ] Nathan - Bring GAAD blog post to completion. Publish 5/12.
  - [ ] Jamie/Rob - COmplete [spreadsheet](https://docs.google.com/spreadsheets/d/1q4DkaNwH8mh7xZJa1TmrHNcFuFuWdQ80iG88c7N4QII/edit#gid=0) for list of projects and issues for GAAD.
  - [ ] Suz/David/Melanie - Contact organizers of projects from above spreadsheet.
  - [ ] All - GAAD Outreach
    - [ ] Ember Weekly
    - [ ] CodePen
    - [ ] Léonie Watson
    - [ ] CodePen
    - [ ] ClearLeft
    - [ ] Mozilla Evangelists Group
    - [ ] Jennison
    - [ ] Ember community.
    - [ ] web-a11y slack.
    - [ ] Our company's Twitter accounts.
- [ ] Ben/Rob - Organize speaking at Ember ATX.

## Discussion Notes

### GAAD - May 19

- Revise blog post.
- Focus in the scope on what we're trying to do.
- Get consent from a few addons on our focus.
- Push blog post to emberjs blog?
- Google doc for the projects and issues.
  - Can be non-ember but foundational plugins (pikaday).
- Offer all-day pairing. (Rob, Nathan, others?)
- Regular meetup that day for A11y Chicago, promote to Ember Chicago.
- Possibly drop ember-a11y into the [open source Ember.js applications](https://www.icicletech.com/blog/16-opensource-emberjs-projects-to-learn-from).

### SF Ember Meetup - Ben

- Ben speaking at [17th May 2016 Ember SF meetup](http://www.meetup.com/Ember-SF/events/230149300/) - half hour talk
- Promote GAAD at the meetup.
- Draft slides to follow, would really appreciate feedback from y'all.
- General introduction to accessibility tooling and what we can do in Ember.js
- Focus on JS A11y tooling that exists and making this apply to Ember and the Ember community.

## Demo site

- Do we really want container view/collection view (weren't they deprecated for 2.0?)
  - Until the version of Ember we're using for the a11y-demo-app drops support for a feature we should include them in the demo application.
- Include the addons for 5/19 into the demo application.
  - Link the issue document.
- Proposing a bit of structure - 
  - Option 1: Native Ember vs Addon
    - Addons - but how to sort these? Position on ember-observer.
  - ~~Option 2: By more of a category (maybe grouped by functionality?)~~

## ember-aXe / ember-a11y-testing

- Gathering thoughts/advice on [https://github.com/trentmwillis/ember-axe/pull/6](https://github.com/trentmwillis/ember-axe/pull/6).
- Will enable this to be inside of CI for Kickstarter.
- Currently broken on 2.X.
