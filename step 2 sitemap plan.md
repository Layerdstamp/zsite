# Step 2 Sitemap Plan

## Planning Objective

Define a clean site structure for one domain that contains:

- a minimal link-tree style homepage
- a full internal art portfolio website
- a full internal A Look Into My Life website

This plan is focused on structure, content grouping, naming, and route logic only. It does not define visual style yet.

## Master Site Model

The combined domain should be treated as one branded ecosystem with three primary experiences.

1. Home
- Role: front door
- Function: quick identity, social access, and entry point to the two deeper worlds

2. Art
- Role: portfolio branch
- Function: internal art website containing the rebuilt content from the current art site

3. A Look Into My Life
- Role: editorial / personal world branch
- Function: internal lifestyle and article-based website with future premium content inside it

## Primary Sitemap

### `/`

Public landing page.

Purpose:
- identity
- immediate access to socials
- immediate access to the two main site branches

Required content:
- banner / hero area
- short intro or name presentation
- Instagram
- TikTok
- Email
- Art entry button
- A Look Into My Life entry button

Constraint:
- keep the homepage minimal

### `/art`

Public art website.

Purpose:
- showcase creative work and visual identity
- absorb and replace the current external art-site experience

Core sections to plan for under Art:
- featured work
- collections or categories
- about the artist
- my skills
- contact or inquiry

Working rule:
- About Me and My Skills should match the structure and tone of the existing art site rather than being forced into the lifestyle branch

### `/a-look-into-my-life`

Public-facing entry to the lifestyle / editorial branch.

Purpose:
- present a softer personal world
- hold article-driven and image-driven content
- serve as the parent branch for lifestyle categories

Tone goal for structure:
- intimate
- thoughtful
- feminine
- aspirational

## A Look Into My Life Internal Structure

The current folder structure should be reorganized into clearer public-facing categories.

### Core category areas

1. Spirituality
- purpose: writing, reflection, healing, inner life, feminine spirituality
- current source mapping: [Homepage/Learning Spirtuality](Homepage/Learning%20Spirtuality)
- public-facing name recommendation: Spirituality

2. Womanhood
- purpose: positive messaging for women, relatable writing, values, relationships, self-respect, becoming a good woman in your own voice
- current source mapping: [Homepage/Woman Empowerment](Homepage/Woman%20Empowerment)
- public-facing name recommendation: Womanhood

3. Style
- purpose: finding your style, outfit building, dressing well without needing expensive fashion, confidence through presentation
- current source mapping: [Homepage/Shopping](Homepage/Shopping)
- public-facing name recommendation: Style

4. Travel
- purpose: favorite places, visual travel memories, small photo stories, location-based highlights
- current source mapping: not yet clearly separated in the current repo
- public-facing name recommendation: Travel

5. See More Of Me
- purpose: personal visual storytelling, public extra galleries, softer behind-the-scenes image world
- current source mapping: [Homepage/See More Of Me](Homepage/See%20More%20Of%20Me)
- public-facing name recommendation: See More Of Me or Personal Moments

6. Private Content
- purpose: gated premium image content that goes beyond the public-facing lifestyle material
- current source mapping: [Homepage/A look in my life page/Additional Image Folders beyond oayment wall](Homepage/A%20look%20in%20my%20life%20page/Additional%20Image%20Folders%20beyond%20oayment%20wall)
- public-facing name recommendation: Private Gallery, Members Area, or Inner Circle

## Folder-To-Sitemap Mapping

This is the logical cleanup direction based on the current repo.

- [Homepage/Art page](Homepage/Art%20page)
  - maps to: Art branch

- [Homepage/About Me](Homepage/About%20Me)
  - maps to: Art branch, unless the scraped art site reveals a better structure

- [Homepage/My skills](Homepage/My%20skills)
  - maps to: Art branch, aligned with current art-site identity

- [Homepage/Links to socials](Homepage/Links%20to%20socials)
  - maps to: homepage utility actions, not a major branch

- [Homepage/A look in my life page](Homepage/A%20look%20in%20my%20life%20page)
  - maps to: parent concept for A Look Into My Life

- [Homepage/Learning Spirtuality](Homepage/Learning%20Spirtuality)
  - maps to: A Look Into My Life > Spirituality

- [Homepage/Woman Empowerment](Homepage/Woman%20Empowerment)
  - maps to: A Look Into My Life > Womanhood

- [Homepage/Shopping](Homepage/Shopping)
  - maps to: A Look Into My Life > Style

- [Homepage/See More Of Me](Homepage/See%20More%20Of%20Me)
  - maps to: A Look Into My Life > See More Of Me

## Naming Cleanup Plan

These are clearer names for public structure.

- A look in my life page -> A Look Into My Life
- Learning Spirtuality -> Spirituality
- Woman Empowerment -> Womanhood
- Shopping -> Style
- Additional Image Folders beyond oayment wall -> Private Gallery or Members Area

Notes:
- internal storage names can stay different if needed
- public-facing names should feel intentional and polished

## Content Rules For Migration

These rules should guide all future extraction and rebuild work.

1. Preserve all existing material
- every image from the existing websites is intended to be reused
- every written description from the existing websites is intended to be preserved

2. Reorganize, do not randomly trim
- the goal is not to simplify by throwing away content
- the goal is to restructure the material into a cleaner multi-branch system

3. The homepage is not the content dump
- most written and image-heavy material should live in Art or A Look Into My Life

4. Premium content belongs inside the lifestyle branch
- premium images should not become a disconnected top-level website area

## Recommended Route Direction

These routes are the cleanest current planning placeholders.

- `/`
- `/art`
- `/a-look-into-my-life`
- `/a-look-into-my-life/spirituality`
- `/a-look-into-my-life/womanhood`
- `/a-look-into-my-life/style`
- `/a-look-into-my-life/travel`
- `/a-look-into-my-life/see-more-of-me`
- `/a-look-into-my-life/private-gallery`

These route names can still change later, but this structure is coherent enough to plan against.

## Questions Deferred To Later Steps

These should remain deferred for now because this step is structure-only.

- exact visual direction
- animation language
- exact banner replacement image
- paywall implementation mechanics
- hosting and deployment configuration

## Outcome Of Step 2

This sitemap plan establishes:

- one domain with three primary experiences
- the homepage as a minimal portal rather than a content-heavy page
- Art as a portfolio branch
- A Look Into My Life as the lifestyle and editorial branch
- a cleaner mapping of the current jumbled folders into a usable site structure