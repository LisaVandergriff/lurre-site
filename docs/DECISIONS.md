# Lurre — Master Decisions

> Last updated: October 5, 2026
>
> This document is the source of truth for decisions that apply to the
> Lurre parent brand, Lurre.co, and the relationship between projects
> within the Lurre ecosystem.
>
> Each individual Lurre project maintains its own `docs/DECISIONS.md`
> for project-specific decisions.
>
> Ideas being discussed are NOT decisions. Do not add them here until
> they have been intentionally adopted.

---

# 1. LURRE

**Lurre** is the parent / umbrella brand.

Lurre is not limited to one business model, product type, community,
story, store, or creative discipline.

It exists as the home for ideas that may become:

- communities
- stories
- digital spaces
- physical products
- creative experiments
- tools
- experiences
- future projects that do not yet have names

The core idea is that Lurre provides a home for ideas to become
something real.

---

# 2. CORE BRAND IDEA

The established Lurre brand line is:

**Ideas become places.**

This is the central organizing idea behind the Lurre ecosystem.

A "place" does not have to mean a literal physical location.

A place can be:

- a website
- a community
- a fictional world
- a creative studio
- a shared conversation
- a digital experience
- a product ecosystem
- somewhere people return to

Lurre creates the container.

Individual projects create distinct places inside that larger world.

---

# 3. BRAND POSITIONING

Lurre should feel:

- creative
- curious
- thoughtful
- warm
- sophisticated
- slightly unexpected
- personal without being amateur
- polished without becoming corporate
- flexible enough to contain very different projects

Lurre should NOT feel like:

- a conventional corporate holding company
- a generic marketing agency
- an Etsy storefront
- a personal résumé site
- a social-media link page
- a collection of unrelated side hustles

The projects may be different.

The curiosity behind them is the common thread.

---

# 4. BRAND VOICE

Lurre's voice should feel:

- intelligent
- conversational
- curious
- warm
- lightly witty
- confident without being self-important

It can acknowledge that ideas sometimes grow beyond their original
scope.

That is part of the personality of the brand rather than something to
hide.

An established example of this tone is:

**"And whatever comes next."**

Another is:

**"occasionally gotten a little carried away with."**

The voice should not become overly formal simply because Lurre is the
parent brand.

---

# 5. PRIMARY DOMAIN

Primary Lurre domain:

**https://Lurre.co**

Preferred public form:

**Lurre.co**

The production website is hosted through Vercel.

The Lurre site is maintained through GitHub and local development in
VS Code.

---

# 6. LURRE ECOSYSTEM

Current Lurre structure:

```text
Lurre
├── Meet on the Porch
├── Sadie's World
├── Lurre Studio
└── Future projects
```

This structure is intentionally expandable.

New projects may be added without requiring Lurre itself to be
redefined.

---

# 7. PROJECT INDEPENDENCE

Projects within Lurre are related but are NOT required to look or
behave identically.

Each project may have its own:

- audience
- visual identity
- tone
- domain
- functionality
- content model
- community model
- business model
- development roadmap

Lurre provides the umbrella identity.

It does not flatten every project into one aesthetic or product.

---

# 8. PROJECT DECISION OWNERSHIP

Each significant project should maintain:

```text
docs/
└── DECISIONS.md
```

The project's `DECISIONS.md` is the source of truth for decisions
specific to that project.

The Lurre Master `DECISIONS.md` should contain only enough information
about a child project to establish:

- what the project is
- where it belongs in the Lurre ecosystem
- its primary domain
- major cross-project relationships
- decisions that affect Lurre as a whole

Detailed project canon belongs in the child project's own decision
record.

---

# 9. DECISION HIERARCHY

Decision ownership should follow this rule:

## Lurre Master

Use this file for decisions involving:

- Lurre branding
- Lurre.co
- umbrella architecture
- shared infrastructure
- cross-project standards
- project relationships
- shared navigation/discovery
- newsletter infrastructure
- shared email/domain strategy
- ecosystem-wide decisions

## Project DECISIONS.md

Use the project's file for:

- project audience
- product behavior
- project-specific features
- project-specific visual systems
- characters or story canon
- community rules
- project-specific monetization
- project-specific technical architecture
- project-specific content strategy

If a decision affects both levels, summarize it here and record the
full decision in the appropriate project file.

---

# 10. MEET ON THE PORCH

**Meet on the Porch** is an independent project within Lurre.

Primary domain:

**https://MeetOnThePorch.com**

High-level purpose:

A presence-first social space centered around spontaneous conversation,
repeated presence, and the simple question:

**"Who's here?"**

Meet on the Porch is not the same product as Lurre.

Lurre may introduce and link to The Porch, but detailed Porch product
decisions belong in:

```text
Meet on the Porch
└── docs/
    └── DECISIONS.md
```

The Porch's detailed feature set, community behavior, safety model,
audience research, competitive research, and product philosophy should
NOT be duplicated into this master file.

---

# 11. SADIE'S WORLD

**Sadie's World** is an independent project within Lurre.

Primary domain:

**https://SadiesWorld.co**

High-level purpose:

An adult creative/storytelling world centered around mature female
curiosity, fantasy, identity, and exploration.

Sadie's World intentionally has a darker and more sensual identity than
the Lurre parent brand.

Lurre may introduce and link to Sadie's World without forcing Sadie's
World to adopt Lurre.co's warm cream visual system.

Detailed Sadie's World decisions belong in:

```text
Sadie's World
└── docs/
    └── DECISIONS.md
```

Character canon, writing rules, adult-content direction, audience
strategy, visual canon, and Sadie-specific decisions should NOT live in
this master file.

---

# 12. LURRE STUDIO

**Lurre Studio** is the maker / physical-product side of the Lurre
ecosystem.

Current primary storefront:

**Etsy — Lurre Studio**

Lurre Studio may include:

- 3D printed pieces
- miniatures
- decorative objects
- creative products
- other physical maker projects

Lurre Studio originally had a larger role in Lurre's web identity.

That positioning has been superseded.

**Lurre.co is no longer an Etsy-centric Lurre Studio website.**

Lurre Studio is now one project within the broader Lurre ecosystem.

Detailed product, licensing, pricing, marketplace, and maker decisions
belong in Lurre Studio's own project records rather than this master
file.

---

# 13. LURRE.CO PURPOSE

Lurre.co is the front door to the Lurre ecosystem.

Its job is to:

1. establish what Lurre is
2. create the overall brand atmosphere
3. introduce current projects
4. provide paths into those projects
5. allow visitors to follow what develops next
6. provide a way for people with useful skills or ideas to make contact

Lurre.co should NOT attempt to reproduce the full functionality or
content of each child project.

It introduces.

The projects themselves provide depth.

---

# 14. CURRENT LURRE.CO PAGE STRUCTURE

Current primary pages:

```text
index.html
connect.html
confirm.html
welcome.html
```

Purpose:

### `index.html`

Main Lurre landing page.

Introduces:

- Lurre
- brand philosophy
- current projects
- future-project mindset
- About
- path to Connect

### `connect.html`

Connection hub.

Provides two primary paths:

- Follow Along
- Bring Something to the Table

### `confirm.html`

Newsletter subscription confirmation landing page.

Used after someone submits their subscription and needs to confirm their
email address.

### `welcome.html`

Confirmed-subscriber landing page.

Used after email confirmation is complete.

---

# 15. PRIMARY SITE NAVIGATION

The shared primary navigation is:

**HOME · PROJECTS · ABOUT · CONNECT**

The previous top-right:

**EXPLORE LURRE →**

header button has been intentionally removed.

Reason:

It duplicated the existing Projects navigation and added unnecessary
visual weight.

Do not reintroduce a fifth header CTA without a new functional reason.

---

# 16. "EXPLORE LURRE" CTA RULE

Removing the header button does NOT mean the phrase "Explore Lurre"
cannot be used elsewhere.

Contextual calls-to-action remain appropriate.

Examples currently retained include:

- Home hero exploration CTA
- Welcome-page Explore Lurre button

The distinction is:

**Redundant header navigation was removed. Contextual CTAs remain.**

---

# 17. LURRE.CO VISUAL SYSTEM

The approved Lurre.co direction is:

- warm cream
- espresso / deep brown
- muted gold
- elegant serif typography
- restrained handwritten/script accents
- atmospheric photography
- generous spacing
- polished editorial feel

The site should feel creative and warm rather than corporate.

---

# 18. TYPOGRAPHY

Current Lurre.co typography includes:

**Cormorant Garamond**

Used for primary serif/editorial typography.

**Italianno**

Used for handwritten/script accents.

The script treatment should remain selective.

It is an accent, not the primary body font.

---

# 19. HEADER BRANDING

The Lurre header uses:

- simple circular **L** mark
- spaced **LURRE** wordmark

This simple treatment is intentional.

Do NOT replace the header mark with the more ornate full Lurre branding
art unless the overall header design is intentionally reconsidered.

The header should remain visually light.

---

# 20. HERO BRANDING

The primary Lurre hero uses:

```text
Lurre_Background_hero1.png
```

with:

```text
Lurre_Branding_Overlay.png
```

The branding overlay is the intended hero branding asset.

Do not casually substitute:

```text
Lurre_MainLogo.png
```

for the hero overlay.

The MainLogo asset may have other uses, but it is not the default hero
overlay.

---

# 21. HOME HERO

Current established Home hero language includes:

**Ideas become places.**

Supporting concept:

**A home for things imagined, made, written, built — and occasionally
gotten a little carried away with.**

The hero establishes Lurre itself before introducing individual
projects.

---

# 22. HOME PROJECT SECTION

The primary project section is introduced with:

**INSIDE LURRE**

and:

**Different Places. Same Curious Mind.**

Current featured projects:

1. Meet on the Porch
2. Sadie's World
3. Lurre Studio

The project cards should link visitors out to the actual project or
store rather than trying to recreate each project inside Lurre.co.

---

# 23. MEET ON THE PORCH CARD

Current high-level card positioning:

**Meet on the Porch**

Tagline:

**Come as you are. See who's here.**

CTA:

**VISIT THE PORCH →**

Destination:

**https://MeetOnThePorch.com**

Current Lurre landing-page image asset:

```text
ThePorch_hero1_landingpage.jpg
```

---

# 24. SADIE'S WORLD CARD

Current high-level card positioning:

**Sadie's World**

Tagline:

**Something is waking up…**

CTA:

**ENTER SADIE'S WORLD →**

Destination:

**https://SadiesWorld.co**

Current Lurre landing-page image asset:

```text
SadiesWorld_hero1_landingpage.png
```

---

# 25. LURRE STUDIO CARD

Current high-level card positioning:

**Lurre Studio**

Tagline:

**Made to inspire. Designed to delight.**

CTA:

**VISIT THE STUDIO →**

Current destination:

**https://etsy.com/shop/LurreStudio**

Current Lurre landing-page image asset:

```text
Lurre_Studio_hero1_landingpage.png
```

---

# 26. FUTURE PROJECT POSITIONING

The Lurre home page intentionally includes the idea:

**And whatever comes next.**

This communicates that Lurre is designed to expand.

Future projects do not need to be predicted or represented by empty
placeholder cards.

Add them when they become real enough to introduce.

---

# 27. HOME "STAY CONNECTED" STRATEGY

The Home page should NOT duplicate the full Connect experience.

Home provides a teaser that directs visitors to `connect.html`.

Current direction includes:

**STAY CONNECTED**

**There's more than one way to be part of what comes next.**

Supporting copy:

**Follow the ideas as they grow — or bring something of your own to the
table.**

Script line:

**Curious to see where this goes?**

CTA:

**CONNECT WITH LURRE →**

---

# 28. CONNECT PAGE PURPOSE

The Connect page provides two distinct paths.

## Follow Along

For visitors who want updates as projects evolve.

## Bring Something to the Table

For people who see something they may be able to help build, improve,
market, design, organize, or grow.

These two intentions should remain distinct.

Following Lurre does not imply volunteering or collaborating.

Offering skills does not require joining a newsletter.

---

# 29. COLLABORATION POSITIONING

The established collaboration concept is:

**Bring Something to the Table**

The tone should feel open and curious rather than like a corporate
recruiting page.

Current areas of possible contribution include:

- Design
- Development
- Marketing
- SEO
- Community
- Creative

Public collaboration contact:

**hello@lurre.co**

Current Connect-page email CTA uses this address.

---

# 30. CONNECT CLOSING PRINCIPLE

Established closing copy:

**You don't need to know exactly where you fit. If something here made
you curious, that's enough.**

This captures the intended low-pressure nature of Lurre discovery and
collaboration.

---

# 31. NEWSLETTER PLATFORM

Current newsletter infrastructure:

**Buttondown**

Current Buttondown newsletter/account identity:

**LisaLurre**

Newsletter name:

**Lurre**

Buttondown is infrastructure.

It should not become the visible identity of the Lurre brand where
custom Lurre presentation is possible.

---

# 32. NEWSLETTER DESCRIPTION

Current Lurre newsletter description:

**Lurre is where ideas become places — communities, stories, creative
projects, and whatever comes next. Follow along as they take shape,
evolve, and occasionally become something much bigger than originally
planned.**

---

# 33. NEWSLETTER SENDER IDENTITY

Current sender display direction:

**Lisa at Lurre**

Long-term desired sender identity:

**Lisa at Lurre <lisalurre@lurre.co>**

This custom sender should be configured after the Microsoft 365 /
Global Admin issue affecting the Lurre domain email environment has
been resolved.

Do not build long-term email identity around a temporary personal
Outlook address.

---

# 34. LURRE EMAIL ADDRESSES

Long-term intended roles:

### `lisalurre@lurre.co`

Primary Lurre sender/reply identity.

Intended for:

- newsletter sender
- direct Lurre correspondence
- replies from subscribers
- Lisa's Lurre identity

### `hello@lurre.co`

Public collaboration/contact address.

Intended for:

- website inquiries
- Bring Something to the Table
- general Lurre contact

These may eventually route into the same underlying mailbox depending
on the final Microsoft 365 configuration.

---

# 35. BUTTONDOWN SUBSCRIPTION FORM

The custom Lurre Connect form posts to:

```text
https://buttondown.com/api/emails/embed-subscribe/LisaLurre
```

Method:

```text
POST
```

Email field:

```text
name="email"
```

Signup-source metadata:

```text
name="metadata__signup_source"
value="lurre-connect"
```

This field should remain hidden on the custom Lurre form.

---

# 36. NEWSLETTER INTEREST METADATA

The Lurre signup form allows visitors to indicate what they are
interested in hearing about.

Current metadata field:

```text
metadata__interests
```

Current values:

```text
lurre
the-porch
sadies-world
lurre-studio
```

Display labels:

- Lurre
- The Porch
- Sadie's World
- Lurre Studio

These interests allow future newsletter content to become more relevant
without requiring separate newsletter systems for every project.

---

# 37. BUTTONDOWN SUBSCRIPTION SETTINGS

Current established settings include:

- Public subscriptions: ON
- Subscription reminders: ON
- Subscriber cleanup: ON
- Welcome email: ON

Buttondown's paid-only customization features are not required at the
current stage.

Do not upgrade solely for cosmetic customization unless there is a
clear benefit.

---

# 38. SUBSCRIPTION FLOW

Intended Lurre subscription flow:

```text
Lurre Connect page
        ↓
Buttondown subscription
        ↓
Lurre confirmation page
        ↓
Buttondown confirmation email
        ↓
Lurre welcome page
```

Intended public clean URLs:

```text
https://lurre.co/confirm
https://lurre.co/welcome
```

These clean routes must be verified in production.

---

# 39. CONFIRM PAGE

Purpose:

Tell the visitor that their subscription request was received and that
they need to confirm their email.

Established primary content:

**ALMOST THERE**

**Check your inbox.**

Script:

**One tiny click and you're in.**

The page should remain simple.

It is a utility step in the signup flow, not another marketing landing
page.

---

# 40. WELCOME PAGE

Purpose:

Acknowledge successful confirmation and return the visitor to the Lurre
world.

Established primary content:

**WELCOME TO LURRE**

**You're in.**

Script:

**Glad you found your way here.**

The contextual:

**EXPLORE LURRE →**

button remains appropriate on this page.

---

# 41. CONFIRM + WELCOME VISUAL RULE

Confirm and Welcome intentionally use a simpler visual hierarchy than
Home and Connect.

They share:

- Lurre header
- Lurre background world
- cream content card
- serif typography
- script accent
- espresso and gold palette

They do NOT need the large Lurre branding overlay used on the primary
Home and Connect experiences.

They are paired utility pages and should remain visually related.

---

# 42. NEWSLETTER EMAIL DESIGN

Current Buttondown email template:

**Modern**

Current general email direction:

- Lurre identity
- simple editorial presentation
- warm gold/brown accent
- readable body content
- restrained branding

Buttondown custom CSS requires a paid tier and is intentionally deferred.

Do not pay solely to reproduce the full website design inside email at
this stage.

---

# 43. NEWSLETTER EMAIL HEADER

Current simplified newsletter header:

**LURRE**

*Ideas become places.*

Raw HTML should not be placed into Buttondown fields that render it as
literal text.

Use supported Markdown/plain formatting unless paid/custom
functionality is intentionally adopted.

---

# 44. NEWSLETTER EMAIL FOOTER

Current footer direction:

*Until the next idea gets out of hand,*

**Lisa**

LURRE

*Ideas become places.*

This deliberately keeps Lisa present as the person behind Lurre.

---

# 45. FUTURE NEWSLETTER VISUAL DIRECTION

If greater Buttondown customization becomes worthwhile later, the
preferred direction is:

**dark espresso atmosphere → warm cream reading area → restrained gold
Lurre details**

The goal is NOT full dark-mode email with large amounts of white body
text.

The preferred experience is closer to a warm letter presented inside
the darker Lurre world.

This is a future direction, not a current implementation requirement.

---

# 46. BUTTONDOWN HOSTED PAGE

Buttondown also provides a hosted public subscription page.

The custom Lurre Connect page is the preferred subscription experience.

Buttondown's hosted page may remain available as infrastructure but
should not drive the visual identity of Lurre.

---

# 47. SOCIAL LINKS

Lurre social links have not yet been finalized for the parent site /
newsletter.

Do not add random or incomplete social accounts simply to fill space.

Add social links when the intended Lurre-level channels are clear.

---

# 48. SHARE IMAGE

A deliberate Lurre social/share image has not yet been finalized.

Buttondown's share-image field may remain blank until an intentional
Lurre share asset is created.

Do not use an arbitrary image simply to fill the setting.

---

# 49. PRIVACY & DISCLOSURE

Lurre should eventually have a dedicated:

**Privacy & Disclosure**

page.

The footer should eventually provide access to it.

Individual projects may require their own privacy/disclosure language
depending on what they collect and how they operate.

A Lurre master policy should not automatically replace project-specific
requirements.

---

# 50. TECHNICAL PLATFORM

Current Lurre.co development/deployment stack:

- VS Code
- Git
- GitHub
- Vercel
- HTML/CSS
- Buttondown for newsletter infrastructure

The architecture should remain as simple as practical.

Do not introduce frameworks, databases, or additional services without
a real product requirement.

---

# 51. GITHUB REPOSITORY

Current Lurre parent-site repository:

```text
LisaVandergriff/lurre-site
```

Primary branch:

```text
main
```

Local project folder is:

```text
lurre-site
```

Vercel is connected to the GitHub repository and deploys from `main`.

---

# 52. VERCEL

Current Vercel project:

```text
lurre-site
```

Known production destinations include:

```text
www.lurre.co
lurre-site.vercel.app
```

GitHub pushes to the production branch should trigger Vercel
deployment.

Do not manually recreate deployments when normal GitHub/Vercel
deployment is working.

---

# 53. CLEAN URL REQUIREMENT

The production site should support clean public paths such as:

```text
/connect
/confirm
/welcome
```

rather than requiring visitors or external services to see:

```text
/connect.html
/confirm.html
/welcome.html
```

Routing/clean URL configuration should be handled at the site/Vercel
level rather than by creating duplicate pages.

---

# 54. SOURCE CONTROL RULE

Local file state and deployed production state are not the same thing.

A change is not considered deployed merely because it has been saved in
VS Code.

Normal workflow:

```text
Edit
↓
Save
↓
Review locally
↓
Stage
↓
Commit
↓
Push to GitHub main
↓
Vercel deploys
↓
Verify production
```

Do not push visual/code changes merely to see what they look like if
they can be reviewed locally first.

---

# 55. VS CODE STATUS REMINDER

In VS Code Source Control:

```text
M = Modified compared with Git
U = Untracked
A = Added
```

These indicators describe Git state.

They do NOT necessarily mean the file is unsaved.

The editor-tab unsaved indicator should be used to determine whether
current edits still need to be saved.

---

# 56. CURRENT LURRE SITE ASSETS

Current important Lurre parent-site assets include:

```text
Lurre_Background_hero1.png
Lurre_Branding_Overlay.png
Lurre_MainLogo.png
Lurre_Studio_hero1_landingpage.png
SadiesWorld_hero1_landingpage.png
ThePorch_hero1_landingpage.jpg
```

Do not rename working assets casually.

If filenames are changed later, update every page referencing them
before deployment.

---

# 57. RESPONSIVE NAVIGATION

Removing the old header Explore Lurre button must NOT cause the real
navigation to disappear on tablet/mobile.

HOME, PROJECTS, ABOUT, and CONNECT should remain accessible at smaller
screen sizes.

Current responsive strategy allows the navigation to wrap beneath the
brand when necessary.

Mobile usability takes priority over preserving a single-line desktop
header layout.

---

# 58. CROSS-PROJECT DISCOVERY

Lurre may introduce visitors to its child projects.

Child projects may also identify themselves as part of Lurre where
appropriate.

However, cross-promotion should feel like discovering another room in
the same larger creative world.

It should not feel like aggressive funneling between unrelated
products.

---

# 59. CROSS-PROJECT DATA

Do not assume that joining one Lurre project automatically means a user
has joined every other project.

Newsletter interest metadata may be shared at the Lurre level because
the subscriber explicitly chooses interests.

Future accounts, communities, memberships, or private information
should not automatically be shared across projects without an
intentional architecture and appropriate user expectations.

---

# 60. PROJECT NAMING RULE

Use current canonical project names:

**Lurre**

**Meet on the Porch**

**Sadie's World**

**Lurre Studio**

Do not casually shorten or rename projects in official site copy if it
creates ambiguity.

"The Porch" may be used conversationally after Meet on the Porch has
been clearly established.

---

# 61. DOMAIN REFERENCES

Current primary domains:

```text
Lurre
https://Lurre.co

Meet on the Porch
https://MeetOnThePorch.com

Sadie's World
https://SadiesWorld.co

Lurre Studio
https://etsy.com/shop/LurreStudio
```

Use **MeetOnThePorch.com**.

Do not substitute the old/hyphenated form:

```text
meet-on-the-porch.com
```

for the primary Porch domain.

---

# 62. FUTURE PROJECTS

A future idea does not automatically become a Lurre project.

Before adding something to the official ecosystem, it should have
enough definition to answer:

1. What is it?
2. Who is it for?
3. Why does it deserve its own place?
4. Is it actually distinct from an existing Lurre project?
5. Is Lisa genuinely pursuing it rather than simply brainstorming it?

Lurre can hold many ideas.

The website does not need to publish every idea.

---

# 63. MASTER DECISION RULE

Before adding a decision to this file, ask:

**Does this affect Lurre as the parent brand, Lurre.co, shared
infrastructure, or more than one Lurre project?**

If yes:

Record it here.

If it only affects one project:

Record it in that project's `docs/DECISIONS.md`.

If it is only an idea:

Do not record it as a decision yet.

---

# 64. DOCUMENTATION RULE

Important decisions should not exist only in chat history.

When a significant decision is made:

1. Implement it where appropriate.
2. Update the relevant `DECISIONS.md`.
3. If it changes a previous decision, preserve enough history to explain
   what was replaced and why.
4. Do not allow old screenshots, old code, or old chat discussions to
   silently override the current decision record.

---

# 65. RETIRED / SUPERSEDED MASTER DECISIONS

This section exists to prevent old Lurre concepts from being
accidentally resurrected.

## Retired: Lurre.co as primarily an Etsy / Lurre Studio website

Replaced by:

**Lurre as the umbrella brand for multiple projects.**

Lurre Studio remains part of Lurre but is no longer the identity of the
entire parent site.

## Retired: Header "Explore Lurre →" button

Replaced by:

**HOME · PROJECTS · ABOUT · CONNECT**

Contextual Explore Lurre calls-to-action may still be used within page
content.

---

# 66. CURRENT MASTER PRIORITIES

Current Lurre parent-level priorities:

1. Finish and deploy the updated Lurre.co site.
2. Make clean `/confirm` and `/welcome` production routes work.
3. Verify the complete Buttondown subscription flow.
4. Verify subscriber interest/signup-source metadata.
5. Establish project-level `docs/DECISIONS.md` files.
6. Add Lurre Privacy & Disclosure.
7. Resolve Lurre Microsoft 365 / Global Admin email issue.
8. Configure `lisalurre@lurre.co` as the long-term Lurre sender when
   email administration is available.
9. Add social/share assets only when intentionally designed.
10. Continue developing each child project independently under the
    Lurre umbrella.

---

# 67. CURRENT DEPLOYMENT CHECKLIST

Before the next Lurre production push:

- [x] Home header Explore button removed
- [x] Connect header Explore button removed
- [x] Confirm header Explore button removed
- [x] Welcome header Explore button removed
- [x] Home responsive navigation updated
- [x] Connect responsive navigation updated
- [x] Confirm responsive navigation updated
- [x] Welcome responsive navigation updated
- [x] Buttondown Connect form wired
- [x] Buttondown signup-source metadata added
- [x] Buttondown interest metadata added
- [x] Buttondown form no longer intentionally opens a new tab
- [x] Confirm page created
- [x] Welcome page created
- [ ] Configure/verify clean `/confirm` route
- [ ] Configure/verify clean `/welcome` route
- [ ] Review local site one final time
- [ ] Stage current files
- [ ] Commit changes
- [ ] Push GitHub `main`
- [ ] Verify Vercel deployment
- [ ] Test live Home
- [ ] Test live Connect
- [ ] Test live Confirm
- [ ] Test live Welcome
- [ ] Test full live Buttondown subscription flow
- [ ] Verify subscriber metadata

---

# 68. FUTURE MASTER TASKS

Not required for the current deployment:

- [ ] Create Lurre Privacy & Disclosure page
- [ ] Add Privacy & Disclosure footer link
- [ ] Create intentional Lurre social/share image
- [ ] Add Buttondown share image
- [ ] Finalize Lurre-level social links
- [ ] Resolve Microsoft 365 Global Admin issue
- [ ] Establish `lisalurre@lurre.co`
- [ ] Establish/verify `hello@lurre.co`
- [ ] Configure Buttondown custom sender/domain when appropriate
- [ ] Revisit enhanced Buttondown email styling only if worthwhile
- [ ] Create/maintain project-specific decision records

---

# 69. CHANGE LOG

## October 5, 2026

- Created the Lurre Master `docs/DECISIONS.md`.
- Established Lurre as the umbrella/parent brand in the decision record.
- Defined the relationship between Lurre, Meet on the Porch, Sadie's
  World, and Lurre Studio.
- Established that each major child project maintains its own
  `docs/DECISIONS.md`.
- Recorded the current Lurre.co architecture and approved visual system.
- Recorded the shared navigation decision.
- Recorded current Buttondown/newsletter infrastructure.
- Recorded GitHub/Vercel workflow and deployment requirements.
- Recorded current deployment checklist and future master tasks.
- Recorded retired Etsy-centric Lurre positioning.
- Recorded removal of the redundant header Explore Lurre CTA.

---

# 70. GUIDING PRINCIPLE

Lurre does not need every future idea figured out.

Its job is to give good ideas somewhere to become real.

**Ideas become places.**