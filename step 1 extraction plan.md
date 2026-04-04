# Step 1 Extraction Plan

## Goal

Create a custom link tree that replaces the current Bio Sites page, keeps the core social links, and brings the art experience under the same primary domain instead of leaving it as a separate destination.

Hard migration rule: the existing websites are not reference-only. The full existing website content is intended to be carried over, including every image and every written description, then re-themed and re-animated inside the new combined domain structure.

## Source Reviewed

- Source page: https://bio.site/zoelane
- Extraction method: public page render plus raw page source review

## Extracted Live Links

### Core social links to reuse

- Instagram: https://www.instagram.com/solelyzoelane
- TikTok: https://www.tiktok.com/@solelyzoelane
- Email: mailto:solelyzoelane@gmail.com

### Existing art destination

- Current art site link: https://zoelaneeee.wixsite.com/zoelaneart
- Current label on Bio Sites: zoelaneart | art & design

## Extracted Brand / Visual Inputs

- Display name: ❦༺𝒵𝑜𝑒 𝐿𝒶𝓃𝑒༻❦
- Bio text: none currently shown
- Primary background color: #010101
- Primary text color: #c8b59b
- Button background feel: translucent light overlay on dark background
- Primary font family in current profile: Playfair
- Profile image URL: https://media.bio.site/sites/12663cad-c8ab-493d-b4e3-f2f23e9f8c31/tvagYhBhFbDedtBtvawUK7.jpg
- Cover image URL: https://media.bio.site/sites/12663cad-c8ab-493d-b4e3-f2f23e9f8c31/R3fgiGwYNo3dFYoPVq3ij3.jpg
- Art link thumbnail URL: https://media.bio.site/sites/12663cad-c8ab-493d-b4e3-f2f23e9f8c31/LB6JFkKtMb2MerZd4Taz4R.jpg

## What This Means For The New Link Tree

- The new homepage should preserve the three primary contact / social actions:
  - Instagram
  - TikTok
  - Email
- The homepage should remain minimal and act as a branded front door rather than a content-heavy page.
- The homepage should reuse the current banner-style presentation from the existing link page, but with a replacement image.
- The art experience should stop feeling like an off-site branch and instead become part of the same main domain structure.
- The new build should treat the link tree as a branded landing experience, not just a vertical list of buttons.
- The combined site should be understood as one domain with internal branches, not a homepage plus redirects.

## Confirmed Scope Decisions

These decisions are now established and should guide the next planning phase.

1. Homepage behavior
- The homepage is a minimal link tree style landing page.
- Its purpose is quick identity, social access, and entry into the two deeper internal website branches.
- It should keep the current banner-style concept from the existing Bio Sites page, but the banner image will be changed.

2. Art branch behavior
- The art branch is not a redirect.
- It is an internal art website under the same domain.
- Its purpose is portfolio presentation only.
- Public-facing About Me and My Skills content should align with the existing art site structure and tone.

3. A Look Into My Life behavior
- A Look Into My Life is not a redirect.
- It is an internal website under the same domain.
- It should function as a softer members-world or personal world, with articles and editorial-style sections inside it.
- It contains spirituality, womanhood, style, shopping, travel, personal photos, and selected galleries.

4. Content migration rule
- Existing website material is to be migrated comprehensively.
- The working assumption for planning is that every existing image and every existing description should be preserved and brought forward into the new structure.
- The work is a restructure and re-theme, not a selective rebuild.

5. Homepage content limit
- The homepage should stay minimal for the first release.
- Deep content belongs in the Art branch or the A Look Into My Life branch.

## Open Decisions Still Remaining

These items still need confirmation later and should not be assumed yet.

1. Primary domain
- What exact domain should the new custom link tree live on?
- Which final domain will host the combined experience?

2. Exact route naming
- Should the internal branches use routes such as `/art` and `/a-look-into-my-life`, or different public-facing slugs?

3. Paywall implementation path
- The premium personal-photo concept exists, but the access model is still undecided.
- It still needs a later decision on whether it is handled as members-only access, private purchase flow, or another gated structure.

4. Branding direction
- Should the new experience preserve the current black / gold romantic look?
- Or is this a full redesign with a more advanced custom aesthetic?

## Locked Direction For Information Architecture

The site should be planned as one domain with three layers:

1. Home
- Minimal landing page
- Social links
- Entry to Art
- Entry to A Look Into My Life

2. Art
- Internal portfolio website
- Rebuilt from the existing art site content

3. A Look Into My Life
- Internal lifestyle/editorial website
- Houses article categories, personal content, visual storytelling, and future premium content

## Step 1 Extraction Outcome

- The Bio Sites extraction is complete enough to support sitemap planning.
- The homepage role is now defined.
- The art branch role is now defined.
- The A Look Into My Life branch role is now defined.
- The migration rule is now stricter: preserve all existing site material, then reorganize it.

## Step 1 Deliverables Completed

- Recovered the currently live outbound links from Bio Sites
- Captured the current brand styling cues
- Identified the existing external art dependency
- Defined the migration questions that must be answered before architecture and build

## Step 2 Recommendation

After this extraction step, the next step should be an architecture plan that defines:

- final domain usage
- page structure and internal branch routes
- how the existing art-site content maps into the art branch
- how the current repo folders map into A Look Into My Life
- where the premium personal-content concept belongs in the information architecture
- hosting target between GitHub Pages and Cloudflare if anything dynamic is required

## Immediate Blockers

- The main blockers are now narrower.
- The remaining blockers are final domain choice, exact route naming, paywall strategy, and later aesthetic direction.