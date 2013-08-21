Node.js - sky-tumblr-export
================

Export your Tumblr blog to Markdown.


Why?
----

I'm tired of using Tumblr. Well, actually I haven't used Tumblr since 2011. But I wanted the blog posts in Markdown so that I could use a static blog generator. I ultimately wrote my own static blog generator, [sky][sky]. But you can use this to dump your Tumblr blog and use any Markdown static blog generator that you like.


Requirements
------------

You must have [pandoc](http://johnmacfarlane.net/pandoc/) installed. Get it here: http://code.google.com/p/pandoc/downloads/list


Installation
------------

You'll need to install Node.js. You can get it here: http://nodejs.org/download/

    npm install -g sky-tumblr-export


CLI
---

    
    Usage: sky-tumblr-export [options]

    Options:

    -h, --help          output usage information
    -V, --version       output the version number
    -u, --url [url]     REQUIRED. The url of the Tumblr blog.
    -d, --dir <dir>     The directory to dump the files. Default is the current directory.
    -t, --titles        Output titles in markdown.
    --debug             Set to debug mode.
    --api-key <apikey>  The API key. Optional.



Example
------

    sky-tumblr-export -u techneur.com -d /tmp/techneur --titles

### Results: ###

    ├── 2010
    │   ├── 02
    │   │   ├── entrepreneurial-heroes.md
    │   │   ├── inspiration-perishable.md
    │   │   └── meeting-deadlines.md
    │   ├── 03
    │   │   ├── 2-apps-are-better-than-1.md
    │   │   ├── iphone-company-struggle-1.md
    │   │   ├── iphone-company-struggle-2.md
    │   │   ├── its-all-our-fault-why-building-a-business-on-the.md
    │   │   └── social-media-not-about-you.md
    │   ├── 04
    │   │   ├── 5-common-english-errors.md
    │   │   ├── apples-walled-garden-iads-and-html5.md
    │   │   ├── best-customer-word.md
    │   │   ├── business-marriage.md
    │   │   ├── dont-have-the-time.md
    │   │   ├── family-number-one.md
    │   │   ├── finest-way-to-succeed.md
    │   │   ├── five-products-life-easier.md
    │   │   ├── how-bad-do-you-want-it.md
    │   │   ├── iads-secret-sauce-how-apples-recipe-will-cause-a.md
    │   │   ├── ipad-smart-monkey.md
    │   │   ├── it-shouldnt-be-that-hard-right.md
    │   │   ├── rework.md
    │   │   ├── the-best-exercise-any-entrepreneur-can-do.md
    │   │   └── we-have-a-duty.md
    │   ├── 05
    │   │   ├── 1-head-is-better-than-2-or-3-or-4-or-etc.md
    │   │   ├── addicted-to-repetition.md
    │   │   ├── admirable-simplicity.md
    │   │   ├── announcing-mindspread.md
    │   │   ├── business-cards.md
    │   │   ├── business-personality.md
    │   │   ├── detoxify-your-life.md
    │   │   ├── dont-assume-negative.md
    │   │   ├── everyday-stories.md
    │   │   ├── hey-taco-johns-go-f-ck-yourselves-a-failure-to.md
    │   │   ├── idea-sucks.md
    │   │   ├── inspiration-is-not-perishable.md
    │   │   ├── learning-pains.md
    │   │   ├── legacy-is-not-purpose.md
    │   │   ├── less-consumption-more-production.md
    │   │   ├── man-no-arms-no-legs-teach-success.md
    │   │   ├── patience-success-takes-years.md
    │   │   ├── quibids-new-pet-rock.md
    │   │   ├── sport-of-business.md
    │   │   ├── time-to-get-scrappy.md
    │   │   └── two-second-rule.md
    │   ├── 06
    │   │   ├── be-exceptional-and-people-will-market-for-you.md
    │   │   ├── beware-anecdotes.md
    │   │   ├── big-omaha-2010.md
    │   │   ├── compete-on-high-touch.md
    │   │   ├── delivering-happiness-review.md
    │   │   ├── embrace-discomfort.md
    │   │   ├── game-mechanics-web-app.md
    │   │   ├── how-to-make-your-meetings-10x-more-efficient.md
    │   │   ├── if-only.md
    │   │   ├── is-it-actionable-no-then-get-rid-of-it.md
    │   │   ├── just-be-yourself.md
    │   │   ├── microsoft-interview-design-a-kitchen.md
    │   │   ├── mvp-galls-law.md
    │   │   ├── my-son-saved-me-from-complacency.md
    │   │   ├── project-managers-are-from-imaginationland.md
    │   │   ├── software-as-a-vision.md
    │   │   ├── steve-jobs-henry-ford.md
    │   │   ├── time-to-quit-your-job-fight-for-flight-2-of-3.md
    │   │   ├── time-to-quit-your-job-leveraging-the-internet-for.md
    │   │   ├── time-to-quit-your-job-the-motivation-part-1-of-3.md
    │   │   └── too-many-mind-how-your-cell-phone-can-cost-you-the.md
    │   ├── 07
    │   │   ├── a-crappy-vision-is-better-than-lack-of-vision.md
    │   │   ├── a-pessimist-presupposes-failure-an-optimist.md
    │   │   ├── difficult-conversation-failed-customer-interaction-later.md
    │   │   ├── disconnect-to-recharge.md
    │   │   ├── facebook-connects-us-and-disconnects-us.md
    │   │   ├── focus-on-your-customers-and-the-money-will-follow.md
    │   │   ├── give-your-customers-a-story-to-tell.md
    │   │   ├── how-i-got-back-my-mojo.md
    │   │   ├── leverage-simplicity-and-the-desire-for-information.md
    │   │   ├── leveraging-social-capital-eight-circle-of-hell.md
    │   │   ├── managing-up-you-dont-work-in-a-vacuum.md
    │   │   ├── relationships-resumes.md
    │   │   ├── the-dream-gurbaksh-chahal.md
    │   │   ├── use-a-weakness-to-develop-a-strength.md
    │   │   ├── what-monopoly-can-teach-us-about-business.md
    │   │   ├── which-is-better-the-journey-or-the-destination.md
    │   │   ├── will-touchscreen-kill-the-mouse-star.md
    │   │   ├── winning-isnt-everything-its-the-only-thing.md
    │   │   ├── wow-youve-changed.md
    │   │   ├── you-cant-fake-passion.md
    │   │   └── your-call-is-important-to-us.md
    │   ├── 08
    │   │   ├── 100th-post.md
    │   │   ├── better-is-the-enemy-of-good-enough.md
    │   │   ├── curlys-law.md
    │   │   ├── death-of-books.md
    │   │   ├── discipline-is-the-strength-to-do-things-that-will-make.md
    │   │   ├── goodbye-dj-explode.md
    │   │   ├── google-wave-post-mortem-what-entrepreneurs-can-learn.md
    │   │   ├── jack-sparrow-teach-us-about-entrepreneurship.md
    │   │   ├── learning-pains-ii.md
    │   │   ├── loyalty.md
    │   │   ├── luck.md
    │   │   ├── pointing-the-finger-rarely-solves-problems.md
    │   │   ├── scale-to-your-customers-budget-the-opposite-approach.md
    │   │   ├── selling-is-all-about-relationships.md
    │   │   ├── so-you-want-to-become-rich.md
    │   │   ├── steve-jobs-lesson-on-marketing-values-and-belief.md
    │   │   ├── the-startup-idea-filter.md
    │   │   ├── the-trap-is-your-mind.md
    │   │   ├── what-would-motivate-you-to-use-mindspread.md
    │   │   ├── work-hard-play-hard.md
    │   │   └── work-until-your-eyes-bleed.md
    │   ├── 09
    │   │   ├── 10-things-ive-learned-about-the-android-market.md
    │   │   ├── always-build-equity-what-you-can-learn-from-a-pick-up.md
    │   │   ├── apples-new-app-store-guidelines-and-what-they-mean-to.md
    │   │   ├── are-you-a-commodity-foursquare-facebook-location.md
    │   │   ├── commitment-vs-involvement.md
    │   │   ├── deliver-polish-over-features.md
    │   │   ├── distractions-are-the-bane-of-productivity.md
    │   │   ├── entrepreneurship-no-rulebook.md
    │   │   ├── go-web-or-go-home-5-reasons-to-take-your-app-to-the.md
    │   │   ├── its-who-you-know.md
    │   │   ├── kevin-rose-took-a-risk-and-failed.md
    │   │   ├── let-your-customers-determine-your-priority.md
    │   │   ├── mobile-platform-madness-apple-vs-google.md
    │   │   ├── resilience-its-not-how-hard-you-hit-its-how-hard.md
    │   │   ├── solve-your-own-problem.md
    │   │   ├── traction-and-growth-sports-fan-apps.md
    │   │   └── what-mr-tibbles-can-teach-you-about-game-mechanicst.md
    │   ├── 10
    │   │   ├── 40-hours-is-breaking-even.md
    │   │   ├── a-message-to-capital-one-and-other-companies-who-sell.md
    │   │   ├── a-wise-man-learns-from-the-experience-of-others.md
    │   │   ├── announcing-tribal-fan.md
    │   │   ├── apple-sucks-at-upgrades.md
    │   │   ├── be-2nd-to-the-market-and-deliver-the-wow.md
    │   │   ├── build-a-lifestyle-business-or-build-a-social-empire.md
    │   │   ├── change-the-world.md
    │   │   ├── luck-ii.md
    │   │   ├── moving-and-minimalism.md
    │   │   ├── prison-and-taking-things-for-granted.md
    │   │   └── sometimes-completing-a-project-is-better-than-anything.md
    │   ├── 11
    │   │   ├── a-case-for-minimalism.md
    │   │   ├── build-successful-business-app-store.md
    │   │   ├── change-the-world-one-day-at-a-time-lets-help.md
    │   │   ├── changing-schedules-can-force-productivity.md
    │   │   ├── luck-surface-area.md
    │   │   ├── social-media-and-priorities.md
    │   │   ├── the-power-of-the-apology.md
    │   │   ├── things-that-stimulate-your-mind.md
    │   │   └── thorn-in-your-side.md
    │   └── 12
    │       ├── dont-listen-to-the-techies-embrace-chrome-os.md
    │       ├── fear-of-producing-crap.md
    │       ├── regret-minimization-framework.md
    │       ├── start-with-a-vision.md
    │       ├── the-internet-is-too-strong.md
    │       └── yes-i-really-do-want-one-million-dollars.md
    ├── 2011
    │   ├── 01
    │   │   ├── 500-revenue-growth-in-2010.md
    │   │   ├── become-master-of-metaphors.md
    │   │   ├── eric-schmidt-and-the-google-triumvirate.md
    │   │   ├── great-artists-simplify.md
    │   │   ├── i-will-write-an-ebook.md
    │   │   ├── large-iterations-slow-momentum.md
    │   │   ├── make-small-deposits-into-the-bank-of-success.md
    │   │   ├── negativity-fear-and-the-lizard-brain.md
    │   │   ├── positivity-breeds-positivity.md
    │   │   ├── procrastination-is-the-thief-of-time.md
    │   │   ├── review-of-the-google-cr-48-chrome-netbook.md
    │   │   ├── starting-a-software-business-and-finding-a-niche-market.md
    │   │   ├── timely-correspondence.md
    │   │   └── why-are-so-many-logos-blue.md
    │   ├── 02
    │   │   ├── consider-customer-motivations.md
    │   │   ├── customers-demand-native-for-mobile-apps.md
    │   │   ├── dont-let-brain-prevent-your-goals.md
    │   │   ├── fight-the-man-by-building-self-reliance.md
    │   │   ├── legacy-is-greater-than-currency.md
    │   │   ├── pay-per-check-in-adsense-in-the-real-world.md
    │   │   ├── sports-fans-and-identities.md
    │   │   ├── the-success-formula-of-angry-birds.md
    │   │   ├── to-stand-out-you-must-dazzle-your-customers.md
    │   │   ├── unmotivated-get-some-layups.md
    │   │   ├── what-if-tumblr-tumbles-interested-in-a-tumblr-backup.md
    │   │   └── your-language-to-your-customers.md
    │   ├── 03
    │   │   ├── 51-hours-to-live.md
    │   │   ├── a-real-mvp-tale.md
    │   │   ├── diversify-income-streams.md
    │   │   ├── life-is-about-maximizing-the-happiness-function.md
    │   │   ├── not-the-entrepreneurs-manifesto.md
    │   │   ├── the-two-device-productivity-solution.md
    │   │   ├── what-the-successful-will-do-that-you-wont.md
    │   │   └── you-need-an-emergency-fund.md
    │   ├── 04
    │   │   ├── fear-and-loved-ones.md
    │   │   ├── fight-the-rewrite.md
    │   │   ├── literature-and-life.md
    │   │   ├── metaphors-and-marketing.md
    │   │   └── on-this-day.md
    │   ├── 07
    │   │   ├── im-back.md
    │   │   └── victory-for-the-nerds-a-tale-of-recovering-a-stolen.md
    │   ├── 08
    │   │   ├── big-success-requires-accomplishing-small-goals.md
    │   │   ├── forget-the-shiny-tech-focus-on-the-customer-experience.md
    │   │   ├── restaurant-industry-teach-business-customer-expectations.md
    │   │   ├── saddened-by-steves-departure.md
    │   │   ├── sometimes-it-doesnt-matter-what-the-contract-states.md
    │   │   ├── what-does-your-app-do-again.md
    │   │   └── youre-only-as-good-as-your-word.md
    │   ├── 09
    │   │   ├── do-or-do-not-there-is-no-try.md
    │   │   └── we-should.md
    │   ├── 10
    │   │   └── steve-jobs-1955-2011-sharing-his-message.md
    │   └── 11
    │       └── steve-jobs-biography-insanely-great.md
    └── sky
        └── config.json


Contributors
------------

* [JP Richardson](http://github.com/jprichardson)
* [Adam Brault](http://github.com/adambrault)


License
-------

(MIT License)

Copyright 2013, JP Richardson  <jprichardson@gmail.com>


[sky]: https://github.com/skywrite
