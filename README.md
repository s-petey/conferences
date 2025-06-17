# conferences

# React Summit 2025
## SPA to SSR and everything in between
-- Tanner Linsley

10 years ago noticed the shift that react was staring to move to the server.

- SEO
- Perf

using the server to morph react to HTML to be pre registered by the server `renderToString`

---

2020 even with the suppression of memories we added the frameworks and popularity of more react focused tools.

---

Server components -- still a work in progroess, difficult and complex problem to resolve.

Required a new framework to be RSC first which felt very different and challenged what we had been learning for years.

Still even in 2025 it is likely you are using NextJS app router to surface server compoennts as it is the most common standard way to use them.

---

Tradeoffs (exporing for 5 years)

- Complex (env, boundaries, bundlers, hydration, security, dx / debugging)
- Next & Remix to solve these complexities

Server compoennts cause

- Multiplicity (making our apps even more complex)
- Where and when we weave in and out of the server / client bundles and code
- micro and macro changes to code ("use client" / "use server")
- File organization (does X framework require it)

### "Canonical" RSCs

- Remove component data fetching -- no waterfalls
  - Only done with react (sorta) -- requires some router or meta framework
- New data, requires a new server call (server first)
- Lose out on granular invalidation
- Miss optimistic UI
- Bundler support isn't strong (still a WIP)

### RSCs aren't reality for everyone

- Not every use case needs them
- It is likely it could be a huge change, however 85% use client side only apps (state of react latest)
- SSR can still be great
- SPAs are here to stay

### Tanstack

- focus on building tools for the developers today
- Two tools that are built for developers today
  - Tanstack router -- written for TS - works all client
  - Tanstack Start - just a vite plugin <3 - server & srr which is 100% ----------
    - with more coming soon RSC -- soon! -- Dvinci beta

### Tanstack DB

## Becoming a staff engineer

--- Shruti Kapoor

- It is not just about what you do -- it is about who knows about what you do

What is a staff engineer

- Technical leader who makes teams effective
- It is no longer about the work you do directly

Pillars of staff engineer

- Technical Excellence
  - Beyond just building a feature
  - designing systems to scale
  - evaluate technologies
- Organizational impact
  - Talking with stakeholders and across teams ensuring seamless integrations
  - Drive consensus on technical decisions (tech stack / moving tech stack)
- Mentorship and team development
  - Enable other team members (mentorship, onboarding, help others get promoted)
  - Delegate tasks (working with others to cover tasks and focuses for growth)
  - Champion best practices (be passionate, share the passion, and document why)
- Project Leadership
  - own a project without the title of a Product owner or Product manager

---

How to not become a staff engineer

- You are waiting to be told -- you are ready -- you should lead -- you are good enough. You will not be told these things
- You have imposter syndrome is too loud -- learn to manage and prevent it overwhelm you
- Waiting to become a "deep techincal" expert -- before even asking to lead a project
- Don't "Play polotics" - The goal is to make it aware so you can know how to steer and direct your career path.
- I'm not good at networking (don't like it)
  - bring it to others attention (open up with what you want to work on)

---

Find out

- What are you evaluated against
- Where are your current gaps (skill or otherwise)
- Which project you can impact (what project can you own)?
- Who is your support squad?

---

Expectations --

- Tech lead of project
- own the product / lead to figure out requirmenets
- analyze tech and future direction
- figure out missing pieces and working with other teams
- figure out scale - design tech spec
- Design a POC

Steps

- Senior engineer
- 3 technincal project
- 2 mentees
- 1 POC

---

### Think beyond your current team

- Notice repetitive tasks, evaluate proceeses and determine likelyhood of fixes or resolutions
- Deep dive perf on products, have knoledge around the full stack
- Find a way to improve DX
- Gather proof (technical docs, detailed tech analysis, technical discussions you are leading)
- Offer to support your team

### Take initiative
