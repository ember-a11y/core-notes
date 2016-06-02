# ember-a11y Meeting Notes - 2016-06-01

## Attendees

- Nathan Hammond
- Ben Holmes
- Suz Hinton
- Rob DeLuca
- Jamie White
- Will Hastings
- Melanie Sumner
- Amanda - CART

## Actions

- [X] Nathan - Fix the invite bluejeans link.
- [X] Nathan - Rope Mel into the color conversation.
- [X] Nathan - Improve language on email signup.
- [ ] Suz - Scheme for the newsletter.
- [ ] Jamie/Rob - Event inventory.

## Discussion Notes

### GAAD Review

- Number one takeaaway: start earlier. January next year.
- Outreach
  - Very positive response from addon community and maintainers.
  - Lots of followup questions as we hadn't made things clear.
  - Maintainers took time immediately, but that's a lot to ask for.
- Project night at Ember London.
  - Tentative about making the entire night about a11y.
  - One of the best-attended project nights they've had.
  - People seemed to be thrilled about taking on a11y projects.
  - Most people were very excited to get started.
  - Ben and George from Blazie (accessibility consultants) were in attendance and brought a JAWS machine.
    - [Tracked down and submitted an IE fix to Ember Observer.](https://github.com/emberobserver/client/pull/37)
    - [Fixed an aria-hidden bug in ember-tooltips.](https://github.com/sir-dunxalot/ember-tooltips/pull/64)
  - Scheduling a11y project nights for Ember meetups might be good for GAAD.
- Pairing
  - Probably want to communicate more about what to expect:
    - Not Ivory Tower, instead, just casually working together on things.
    - We're here to work with you on whatever you want.
  - Only had one person elect to pair.
  - More people interested in pairing with better timeline and advertisement.
- @rwjblue's Twitch Stream
  - Livestreaming via Twitch could be a great way to showcase what people are working on day of.
  - Drew a fair amount of attention, and the narration helps understand thought processes.
  - People like to work on this stuff and are excited to share it.
  - "Let's play" type videos with a11y topics.
- Afterward Communication
  - People want to share what they're working on.
  - Come up with more avenues for people to promote their work.
  - Find a way to tap into the "competitive nature of programmers."
- Blog Post
  - Good entry point into our activities.
  - Guest post this year but can possibly be an official thing next year.
- Day Of Email
  - Possible newsletter to increase membership for next year?
  - Monthly editions? Suz enjoys this sort of thing.
  - Write consistent content leading up to GAAD next year.
  - Can provide the positive reinforcement and avenue for sharing.
  - 81.6% open rate!
- Experience as a participant?
  - Corporate cheerleading!
  - Evangelical "spreading of the good news."
  - Creates a dialogue internally and builds pride in people's work.
  - "Accessible by default." is a good rallying cry.
- A11y Meetup in Austin
  - Seven people from Deque.
  - A few people involved with the W3C.
  - New connections for us to reach out to!
  - (And leverage their decades of experience.)
- How did we do on promotion?
  - Want to build relationships with a11y community members for better support in the broader community.
  - Start marketing earlier.
  - Promotion internal to the Ember community went excellently.
  - Focus external next year so our efforts don't benefit just us:
    - Work on underlying foundational libraries.
    - A11y primer talk at local meetups leading up to next year.
    - Plan podcast appearances in advance.
  - Start in January!

### State of the Addons

- [ember-a11y](https://github.com/ember-a11y/ember-a11y)
  - Up-to-date with Ember CLI. (Thanks @binhums!)
  - Additional testing scenarios. (Thanks @BrianSipple!)
  - Tested against 1.13. (Thanks @BrianSipple!)
  - Embedded issue reporter. (Thanks @thedig!)
- ember-aXe
  - Deprecated under this name, moved to ember-a11y-testing.
- [ember-a11y-testing](https://github.com/ember-a11y/ember-a11y-testing)
  - Original approach deprecated.
  - ember-aXe merged on top of it.
  - Up-to-date with Ember CLI. (Thanks @noopkat!)
  - Tested against 1.13. (Thanks @noopkat!)
  - Skip testing of fragment components. (Thanks @backspace!)
- [ember-(cli-)template-lint](https://github.com/rwjblue/ember-cli-template-lint)
  - Now includes accessibility linting.
  - [@rwjblue live streamed his work on it!](https://www.twitch.tv/rwjblue/v/67381709)
  - Should be included in our recommendations for accessibility.
  - But wait there's more! [@binhum's PR for linting `alt` existence](https://github.com/rwjblue/ember-template-lint/pull/64)
- [a11y-demo-app](https://github.com/ember-a11y/a11y-demo-app)
  - @melsumner has done a tremendous amount of work on this.
  - Includes lots of popular addons from the community in addition to core Ember components.

### PR News

- Nathan spoke at GEMConf. Video forthcoming.
- Ben talking at Austin meetup at end of June.
- Suz speaking at Ember NYC end of July.
