
# Lurre — Master Decisions

> Last updated: October 9, 2026
>
> This document is the source of truth for decisions that apply to the Lurre parent brand, Lurre.co, and the relationship between projects within the Lurre ecosystem.
>
> Each individual Lurre project maintains its own `docs/DECISIONS.md` for project-specific decisions.
>
> Ideas being discussed are NOT decisions. Do not add them here until they have been intentionally adopted.

---

# 1. LURRE

**Lurre** is the parent / umbrella brand.

Lurre is not limited to one business model, product type, community, story, store, or creative discipline.

It exists as the home for ideas that may become:

- communities
- stories
- digital spaces
- physical products
- creative experiments
- tools
- experiences
- future projects that do not yet have names

The core idea is that Lurre provides a home for ideas to become something real.

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

It can acknowledge that ideas sometimes grow beyond their original scope.

That is part of the personality of the brand rather than something to hide.

An established example of this tone is:

**"And whatever comes next."**

Another is:

**"occasionally gotten a little carried away with."**

The voice should not become overly formal simply because Lurre is the parent brand.

---

# 5. PRIMARY DOMAIN

Primary Lurre domain:

**https://Lurre.co**

Preferred public form:

**Lurre.co**

The production website is hosted through Vercel.

The Lurre site is maintained through GitHub and local development in VS Code.

The root domain redirects to the `www.lurre.co` production destination.

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

New projects may be added without requiring Lurre itself to be redefined.

The guiding operating principle is:

**One brain. Separate projects. Shared learning.**

---

# 7. PROJECT INDEPENDENCE

Projects within Lurre are related but are NOT required to look or behave identically.

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

The project's `DECISIONS.md` is the source of truth for decisions specific to that project.

The Lurre Master `DECISIONS.md` should contain only enough information about a child project to establish:

- what the project is
- where it belongs in the Lurre ecosystem
- its primary domain
- major cross-project relationships
- decisions that affect Lurre as a whole

Detailed project canon belongs in the child project's own decision record.

---

# 9. DECISION HIERARCHY

Decision ownership should follow this rule.

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

If a decision affects both levels, summarize it here and record the full decision in the appropriate project file.

---

# 10. MEET ON THE PORCH

**Meet on the Porch** is an independent project within Lurre.

Primary domain:

**https://MeetOnThePorch.com**

High-level purpose:

A presence-first social space centered around spontaneous conversation, repeated presence, and the simple question:

**"Who's here?"**

Meet on the Porch is not the same product as Lurre.

Lurre may introduce and link to The Porch, but detailed Porch product decisions belong in:

```text
Meet on the Porch
└── docs/
    └── DECISIONS.md
```

The Porch's detailed feature set, community behavior, safety model, audience research, competitive research, and product philosophy should NOT be duplicated into this master file.

---

# 11. SADIE'S WORLD

**Sadie's World** is an independent project within Lurre.

Primary domain:

**https://SadiesWorld.co**

High-level purpose:

An adult creative/storytelling world centered around mature female curiosity, fantasy, identity, and exploration.

Sadie's World intentionally has a darker and more sensual identity than the Lurre parent brand.

Lurre may introduce and link to Sadie's World without forcing Sadie's World to adopt Lurre.co's warm cream visual system.

Detailed Sadie's World decisions belong in:

```text
Sadie's World
└── docs/
    └── DECISIONS.md
```

Character canon, writing rules, adult-content direction, audience strategy, visual canon, and Sadie-specific decisions should NOT live in this master file.

---

# 12. LURRE STUDIO

**Lurre Studio** is the maker / physical-product side of the Lurre ecosystem.

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

Detailed product, licensing, pricing, marketplace, and maker decisions belong in Lurre Studio's own project records rather than this master file.

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

Lurre.co should NOT attempt to reproduce the full functionality or content of each child project.

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

## index.html

Main Lurre landing page.

Introduces:

- Lurre
- brand philosophy
- current projects
- future-project mindset
- About
- path to Connect

## connect.html

Connection hub.

Provides two primary paths:

- Follow Along
- Bring Something to the Table

## confirm.html

Newsletter subscription confirmation landing page.

Used after someone submits their subscription and needs to confirm their email address.

## welcome.html

Confirmed-subscriber landing page.

Used after email confirmation is complete.

## Planned: privacy.html

Dedicated Lurre Privacy & Disclosure page.

Not yet created.

Implementation is deferred while the Microsoft 365 / Global Admin email issue remains unresolved.

---

# 15. PRIMARY SITE NAVIGATION

The shared primary navigation is:

**HOME · PROJECTS · ABOUT · CONNECT**

The previous top-right:

**EXPLORE LURRE →**

header button has been intentionally removed.

Reason:

It duplicated the existing Projects navigation and added unnecessary visual weight.

Do not reintroduce a fifth header CTA without a new functional reason.

---

# 16. "EXPLORE LURRE" CTA RULE

Removing the header button does NOT mean the phrase "Explore Lurre" cannot be used elsewhere.

Contextual calls-to-action remain appropriate.

The Welcome-page **EXPLORE LURRE →** button is intentionally retained.

The approved Home hero does not currently contain an Explore Lurre button.

The distinction is:

**Redundant header navigation was removed. Contextual CTAs may remain where they serve a real purpose.**

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

Established palette includes:

```text
Cream: #faf7f2
Brown: #38271f
Gold:  #c89a58
```

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

Do NOT replace the header mark with the more ornate full Lurre branding art unless the overall header design is intentionally reconsidered.

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

The MainLogo asset may have other uses, but it is not the default hero overlay.

---

# 21. HOME HERO

Current established Home hero language includes:

**Ideas become places.**

Supporting concept:

**A home for things imagined, made, written, built — and occasionally gotten a little carried away with.**

The hero establishes Lurre itself before introducing individual projects.

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

The project cards should link visitors out to the actual project or store rather than trying to recreate each project inside Lurre.co.

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

Future projects do not need to be predicted or represented by empty placeholder cards.

Add them when they become real enough to introduce.

---

# 27. HOME "STAY CONNECTED" STRATEGY

The Home page should NOT duplicate the full Connect experience.

Home provides a teaser that directs visitors to `connect.html`.

Current direction includes:

**STAY CONNECTED**

**There's more than one way to be part of what comes next.**

Supporting copy:

**Follow the ideas as they grow — or bring something of your own to the table.**

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

For people who see something they may be able to help build, improve, market, design, organize, or grow.

These two intentions should remain distinct.

Following Lurre does not imply volunteering or collaborating.

Offering skills does not require joining a newsletter.

---

# 29. COLLABORATION POSITIONING

The established collaboration concept is:

**Bring Something to the Table**

The tone should feel open and curious rather than like a corporate recruiting page.

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

The mailbox's final Microsoft 365 configuration remains pending.

---

# 30. CONNECT CLOSING PRINCIPLE

Established closing copy:

**You don't need to know exactly where you fit. If something here made you curious, that's enough.**

This captures the intended low-pressure nature of Lurre discovery and collaboration.

---

# 31. NEWSLETTER PLATFORM

Current newsletter infrastructure:

**Buttondown**

Current Buttondown newsletter/account identity:

**LisaLurre**

Newsletter name:

**Lurre**

Buttondown is infrastructure.

It should not become the visible identity of the Lurre brand where custom Lurre presentation is possible.

---

# 32. NEWSLETTER DESCRIPTION

Current Lurre newsletter description:

**Lurre is where ideas become places — communities, stories, creative projects, and whatever comes next. Follow along as they take shape, evolve, and occasionally become something much bigger than originally planned.**

---

# 33. NEWSLETTER SENDER IDENTITY

Current sender display direction:

**Lisa at Lurre**

Long-term desired sender identity:

**Lisa at Lurre <lisalurre@lurre.co>**

This custom sender should be configured after the Microsoft 365 / Global Admin issue affecting the Lurre domain email environment has been resolved.

Do not build long-term email identity around a temporary personal Outlook address.

---

# 34. LURRE EMAIL ADDRESSES

Long-term intended roles:

## lisalurre@lurre.co

Primary Lurre sender/reply identity.

Intended for:

- newsletter sender
- direct Lurre correspondence
- replies from subscribers
- Lisa's Lurre identity

## hello@lurre.co

Public collaboration/contact address.

Intended for:

- website inquiries
- Bring Something to the Table
- general Lurre contact

These may eventually route into the same underlying mailbox depending on the final Microsoft 365 configuration.

**Status October 9, 2026:**

Microsoft 365 / Global Admin access remains an unresolved dependency.

Do not assume the intended mailbox configuration is fully operational until verified.

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

The Lurre signup form allows visitors to indicate what they are interested in hearing about.

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

These interests allow future newsletter content to become more relevant without requiring separate newsletter systems for every project.

The final subscriber-record verification remains outstanding.

---

# 37. BUTTONDOWN SUBSCRIPTION SETTINGS

Current established settings include:

- Public subscriptions: ON
- Subscription reminders: ON
- Subscriber cleanup: ON
- Welcome email: ON

Buttondown's paid-only customization features are not required at the current stage.

Do not upgrade solely for cosmetic customization unless there is a clear benefit.

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

These clean routes and the complete new-subscriber experience must be verified in production.

**October 9 status:**

The pages and integration have been created.

A complete fresh-subscriber test, including Buttondown metadata verification, remains pending.

Jenn's test is the next planned validation.

---

# 39. CONFIRM PAGE

Purpose:

Tell the visitor that their subscription request was received and that they need to confirm their email.

Established primary content:

**ALMOST THERE**

**Check your inbox.**

Script:

**One tiny click and you're in.**

The page should remain simple.

It is a utility step in the signup flow, not another marketing landing page.

---

# 40. WELCOME PAGE

Purpose:

Acknowledge successful confirmation and return the visitor to the Lurre world.

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

Confirm and Welcome intentionally use a simpler visual hierarchy than Home and Connect.

They share:

- Lurre header
- Lurre background world
- cream content card
- serif typography
- script accent
- espresso and gold palette

They do NOT need the large Lurre branding overlay used on the primary Home and Connect experiences.

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

Do not pay solely to reproduce the full website design inside email at this stage.

---

# 43. NEWSLETTER EMAIL HEADER

Current simplified newsletter header:

**LURRE**

*Ideas become places.*

Raw HTML should not be placed into Buttondown fields that render it as literal text.

Use supported Markdown/plain formatting unless paid/custom functionality is intentionally adopted.

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

If greater Buttondown customization becomes worthwhile later, the preferred direction is:

**dark espresso atmosphere → warm cream reading area → restrained gold Lurre details**

The goal is NOT full dark-mode email with large amounts of white body text.

The preferred experience is closer to a warm letter presented inside the darker Lurre world.

This is a future direction, not a current implementation requirement.

---

# 46. BUTTONDOWN HOSTED PAGE

Buttondown also provides a hosted public subscription page.

The custom Lurre Connect page is the preferred subscription experience.

Buttondown's hosted page may remain available as infrastructure but should not drive the visual identity of Lurre.

---

# 47. SOCIAL LINKS

Lurre social links have not yet been finalized for the parent site / newsletter.

Do not add random or incomplete social accounts simply to fill space.

Add social links when the intended Lurre-level channels are clear.

---

# 48. SHARE IMAGE

**Updated October 9, 2026**

The official Lurre website social-sharing image has been created and deployed.

Canonical asset:

```text
Lurre_SharingSite_hero1.png
```

Image dimensions:

```text
1734 × 907 pixels
```

The image features Lurre's own branding and the established line:

**Ideas become places.**

It represents the parent Lurre brand rather than an individual child project.

The Home page includes Open Graph and Twitter/X social-preview metadata referencing:

```text
https://lurre.co/Lurre_SharingSite_hero1.png
```

The image must remain accessible through the production website.

## Verified result

On October 9, 2026, an iMessage link preview was confirmed displaying the correct Lurre sharing image.

The initial test displayed The Porch image.

Investigation identified that the updated local Git commit had not yet been pushed to GitHub.

After syncing the commit and allowing the production deployment to update, the correct Lurre preview appeared.

**Website social-sharing image: COMPLETE.**

## Separate Buttondown setting

Buttondown's own share-image configuration is separate from the website's Open Graph metadata.

Do not mark the Buttondown share-image task complete until that setting has been explicitly configured and verified.

---

# 49. PRIVACY & DISCLOSURE

**Updated October 9, 2026**

Lurre will have a dedicated:

**Privacy & Disclosure**

page.

The footer will provide access to it.

The policy should address:

- newsletter email collection
- selected newsletter interests
- signup-source metadata
- Buttondown as a third-party subscription provider
- unsubscribe and data-request options
- applicable cookies and analytics actually used
- relevant affiliate, promotional, or product disclosures
- an appropriate public privacy contact

Do not claim tracking, analytics, or data-processing practices that have not been verified.

Individual projects may require their own privacy/disclosure language depending on what they collect and how they operate.

A Lurre master policy should not automatically replace project-specific requirements.

## Current status

**ON HOLD — Microsoft 365 / Global Admin dependency**

The page has not been implemented.

The final public contact email should be settled after the Microsoft 365 email administration issue is resolved.

Do not create a temporary public privacy contact merely to complete the page.

Resume drafting and implementation after the email decision is finalized.

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

Do not introduce frameworks, databases, or additional services without a real product requirement.

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

GitHub pushes to the production branch should trigger Vercel deployment.

Do not manually recreate deployments when normal GitHub/Vercel deployment is working.

The October 9 social-preview fix confirmed the existing GitHub-to-Vercel deployment workflow.

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

Routing/clean URL configuration should be handled at the site/Vercel level rather than by creating duplicate pages.

Production verification remains on the checklist.

---

# 54. SOURCE CONTROL RULE

**Updated October 9, 2026**

Local file state and deployed production state are not the same thing.

A change is not considered deployed merely because it has been saved in VS Code.

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

Do not push visual/code changes merely to see what they look like if they can be reviewed locally first.

## October 9 deployment lesson

A local Git commit does NOT mean the production website has received the change.

The social-sharing image existed locally and was included in the committed work, but the public image URL initially returned a 404.

Git Graph showed that local `main` was ahead of `origin/main`.

Using VS Code's **Sync Changes** action pushed the commit to GitHub.

Vercel then deployed the updated site.

The social-sharing image became available, and iMessage displayed the correct preview.

**Required verification principle:**

Do not mark a website feature complete until its production behavior has been checked.

For social-sharing images, verify both:

1. The image's public URL loads.
2. A real link preview displays the intended image.

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

The editor-tab unsaved indicator should be used to determine whether current edits still need to be saved.

A committed change may still require a push or sync before it reaches GitHub.

A `.DS_Store` modification is unrelated to the website feature itself and should not be included merely because it appears in Source Control.

---

# 56. CURRENT LURRE SITE ASSETS

**Updated October 9, 2026**

Current important Lurre parent-site assets include:

```text
Lurre_Background_hero1.png
Lurre_Branding_Overlay.png
Lurre_MainLogo.png
Lurre_SharingSite_hero1.png
Lurre_Studio_hero1_landingpage.png
SadiesWorld_hero1_landingpage.png
ThePorch_hero1_landingpage.jpg
```

The sharing image is now an approved production asset.

Do not rename working assets casually.

If filenames are changed later, update every page and metadata reference before deployment.

Filename capitalization and extensions must match exactly.

---

# 57. RESPONSIVE NAVIGATION

Removing the old header Explore Lurre button must NOT cause the real navigation to disappear on tablet/mobile.

HOME, PROJECTS, ABOUT, and CONNECT should remain accessible at smaller screen sizes.

Current responsive strategy allows the navigation to wrap beneath the brand when necessary.

Mobile usability takes priority over preserving a single-line desktop header layout.

The Home and Connect responsive header treatments have been updated.

A final live mobile walkthrough remains outstanding.

---

# 58. CROSS-PROJECT DISCOVERY

Lurre may introduce visitors to its child projects.

Child projects may also identify themselves as part of Lurre where appropriate.

However, cross-promotion should feel like discovering another room in the same larger creative world.

It should not feel like aggressive funneling between unrelated products.

---

# 59. CROSS-PROJECT DATA

Do not assume that joining one Lurre project automatically means a user has joined every other project.

Newsletter interest metadata may be shared at the Lurre level because the subscriber explicitly chooses interests.

Future accounts, communities, memberships, or private information should not automatically be shared across projects without an intentional architecture and appropriate user expectations.

---

# 60. PROJECT NAMING RULE

Use current canonical project names:

**Lurre**

**Meet on the Porch**

**Sadie's World**

**Lurre Studio**

Do not casually shorten or rename projects in official site copy if it creates ambiguity.

"The Porch" may be used conversationally after Meet on the Porch has been clearly established.

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

Before adding something to the official ecosystem, it should have enough definition to answer:

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

**Does this affect Lurre as the parent brand, Lurre.co, shared infrastructure, or more than one Lurre project?**

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
3. If it changes a previous decision, preserve enough history to explain what was replaced and why.
4. Do not allow old screenshots, old code, or old chat discussions to silently override the current decision record.

## Code preservation rule

When modifying an approved Lurre page:

- Use the current approved source file as the master.
- Change only what the task requires.
- Preserve existing CSS, HTML structure, content, and responsive behavior unless explicitly instructed otherwise.
- Do not silently reformat or simplify the entire file.
- Do not treat a shorter rewritten file as equivalent without verification.
- When a complete replacement is requested, provide the complete copy/paste source code directly in the conversation.

Do not substitute a downloadable HTML file or partial code snippet when complete copy/paste code has been requested.

---

# 65. RETIRED / SUPERSEDED MASTER DECISIONS

This section exists to prevent old Lurre concepts from being accidentally resurrected.

## Retired: Lurre.co as primarily an Etsy / Lurre Studio website

Replaced by:

**Lurre as the umbrella brand for multiple projects.**

Lurre Studio remains part of Lurre but is no longer the identity of the entire parent site.

## Retired: Header "Explore Lurre →" button

Replaced by:

**HOME · PROJECTS · ABOUT · CONNECT**

Contextual Explore Lurre calls-to-action may still be used within page content.

## Superseded: No finalized Lurre share image

Replaced October 9, 2026 by:

**Lurre_SharingSite_hero1.png**

The image is deployed and confirmed working in iMessage.

The separate Buttondown share-image setting remains unverified.

---

# 66. CURRENT MASTER PRIORITIES

**Updated October 9, 2026**

Current Lurre parent-level priorities:

1. Complete a fresh-subscriber Buttondown test.
2. Verify subscriber interest and signup-source metadata.
3. Verify production clean routes for `/confirm` and `/welcome`.
4. Complete a final mobile walkthrough of Home, Connect, Confirm, and Welcome.
5. Resolve the Microsoft 365 / Global Admin email issue.
6. Establish and verify the intended Lurre email addresses.
7. Configure the long-term Buttondown sender when email administration is available.
8. Create and publish Lurre Privacy & Disclosure after the contact-email dependency is resolved.
9. Establish or maintain project-level `docs/DECISIONS.md` files.
10. Continue developing each child project independently under the Lurre umbrella.

## Completed since October 5

- Lurre parent site deployed.
- Custom Lurre website social-sharing image created.
- Open Graph / social-preview metadata added.
- Social-sharing image pushed to GitHub and deployed through Vercel.
- Correct Lurre image confirmed in iMessage.
- Approved Home design preserved.

Do not reopen completed site work without a specific issue or new decision.

---

# 67. CURRENT DEPLOYMENT CHECKLIST

**Updated October 9, 2026**

This checklist distinguishes completed implementation from outstanding verification.

## Site implementation

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
- [x] Lurre social-sharing image created
- [x] Home social-sharing metadata added

## Production deployment

- [x] Lurre website deployed through GitHub / Vercel
- [x] October 9 sharing-image commit pushed to GitHub
- [x] Sharing-image production deployment verified
- [x] Public social-sharing image accessible
- [x] Correct Lurre iMessage preview confirmed

## Outstanding verification

- [ ] Configure/verify clean `/confirm` route
- [ ] Configure/verify clean `/welcome` route
- [ ] Complete final live mobile walkthrough
- [ ] Verify live Home navigation
- [ ] Verify live Connect experience
- [ ] Verify live Confirm experience
- [ ] Verify live Welcome experience
- [ ] Test full live Buttondown subscription flow with a fresh subscriber
- [ ] Verify subscriber signup-source metadata
- [ ] Verify subscriber interest metadata
- [ ] Confirm newsletter sender and reply-to behavior after Microsoft resolution

The completed October 9 deployment does not automatically verify every newsletter or mobile function.

---

# 68. FUTURE MASTER TASKS

**Updated October 9, 2026**

## Privacy & contact

- [ ] Resolve Microsoft 365 Global Admin issue
- [ ] Establish/verify `lisalurre@lurre.co`
- [ ] Establish/verify `hello@lurre.co`
- [ ] Finalize privacy contact email
- [ ] Create Lurre Privacy & Disclosure page
- [ ] Add Privacy & Disclosure footer link

## Newsletter

- [ ] Complete fresh-subscriber test
- [ ] Verify subscriber metadata
- [ ] Configure Buttondown custom sender/domain when appropriate
- [ ] Verify Buttondown share-image setting
- [ ] Revisit enhanced Buttondown email styling only if worthwhile

## Branding & discovery

- [x] Create intentional Lurre website social/share image
- [x] Deploy Lurre social-preview metadata
- [x] Confirm correct iMessage sharing preview
- [ ] Finalize Lurre-level social links
- [ ] Add Buttondown share image if appropriate

## Documentation & development

- [ ] Complete final mobile website review
- [ ] Verify clean production routes
- [ ] Create/maintain project-specific decision records
- [ ] Continue cross-project architecture and learning without prematurely coupling projects

---

# 69. CHANGE LOG

## October 9, 2026

- Updated the Lurre Master Decisions document.
- Finalized the Lurre website social-sharing image.
- Established `Lurre_SharingSite_hero1.png` as the canonical website share asset.
- Added Open Graph and Twitter/X preview metadata to the Home page.
- Confirmed the correct Lurre image appears in iMessage.
- Documented the GitHub sync issue that initially prevented the new image from appearing publicly.
- Clarified that local commits must be pushed before Vercel can deploy them.
- Added the sharing image to the approved asset inventory.
- Updated the deployment checklist to distinguish confirmed deployment from outstanding testing.
- Corrected the Home hero Explore Lurre CTA documentation.
- Confirmed Privacy & Disclosure remains planned but on hold pending Microsoft 365 / Global Admin resolution.
- Preserved Buttondown share-image configuration as a separate outstanding task.
- Added the approved-code preservation rule for future website edits.

## October 5, 2026

- Created the Lurre Master `docs/DECISIONS.md`.
- Established Lurre as the umbrella/parent brand in the decision record.
- Defined the relationship between Lurre, Meet on the Porch, Sadie's World, and Lurre Studio.
- Established that each major child project maintains its own `docs/DECISIONS.md`.
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
