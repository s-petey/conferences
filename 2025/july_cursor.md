# Cursor 03 July 2025

## Table of Contents

- [Survey results](#survey-results)
  - [Editor of choice](#editor-of-choice)
  - [Language Model families](#language-model-families)
  - [Project language / framework](#project-language--framework)
  - [AI comprehension in codebase](#ai-comprehension-in-codebase)
  - [Productivity (or not)](#productivity-or-not)
- [Future hope](#future-hope)
- [Other resources](#other-resources) -- Links to podcasts
- [Recap](#recap)

## Practical Ai usage roundup and discussion

### Introduction:

I’m Sam, from USA, but now happily living in Denmark. I’ve been programming full stack since 2018. Recently I’ve been looking to really sharpen my Ai skillset. As always I’ve been trying to stay up to date on most new development focused theories and technology. As Fernando stated I’m more of an Ai skeptic, but am open and wanting to learn more and how it can impact our daily lives.

### Goals of talk

This is meant to be a discussion with you, the community, and me sharing the journey of how I’ve been trying to sharpen my Ai skills. This isn’t just how I work with Ai as a tool, but the way others may interact too.

### What it means

I’ve historically only seen Ai as a tool to enhance my daily working experience. With the discussion and recent findings I’ve been learning it can be used as a pair coder. Or a JR developer which I can assign to take on tasks on my behalf.

### Survey results

[Source](https://docs.google.com/forms/d/1w036jlBwo8o_xjN1nRVRCyZ6ZTpVAfgHToSZHHYfAjg/edit#responses)

- Editor of choice
  - Obviously this being a Cursor meetup it was skewed that way, however in my workplace, which some included their responses, I see the use of Cursor surpass most other editors.
    - I think the most talked about feature is the “next edit suggestion” which is what VSCode calls it. This is a feature that suggests the next line which may need to be modified based on a recent edit you have made.
      - Show the docs / videos → https://code.visualstudio.com/docs/copilot/ai-powered-suggestions#_next-edit-suggestions
    - Another reason I’ve heard is the UI experience with the AI, I have no tips or tricks there, but over time I’ve seen VSCode improve.
  - Next is Windsurf usage, for a very similar product which I’ve used in VSCode previously I’m surprised more people haven’t tried or stuck to that.
  - I’d like to ask if anyone here has heard of Zed, a project to make a ground up different editor leveraging the GPU rendering and layering UI elements. It also has better VIM motion support and some really nice tooling within the editor.
  - Lastly VIM - NeoVim — I’ve been on this journey several times, and this time it may stick! I’ve been liking it a lot, mostly.
- Ways of prompting
  - I’m very surprised by the difference in results here from my own interaction. Typically I’m the only AI autocomplete my code. I then get angry when it uses an array instead of a Map for different logic. Small things which I’m sure I could provide context to “sharpen” its usefulness.
  - I’ve also heard a lot about using more terminal based editors and working with git worktree. I still haven’t learned about them other than it can allow editing different files for different features on the same repository at the same time.
    - This has enabled people to do some amazing things. Prompting the terminal based agents to complete the AC for a task, going and making a coffee while waiting for the results to come back or working on a different area of the code base for a different feature that may be too complex for the AI at the same time.
    - This workflow fascinates me and genuinely I think this is the future of programming. You give it some small AC and it will make the foundation for the changes and suddenly _ding_ 🛎️ your feature is complete! You may need to tweak it a bit, bake it a bit longer, but you are still honing that AI tool in your toolbelt here.
- Use frequency
  - Gloss over as not much to add there.
- Use cases
  - Fixing existing code
    - What does this say about our “sharpness” of skills? Have we been maintaining it, what is the reason an AI agent is beating us to make this better? Because it is simple and we don’t have to think about it.
    - I’d like to ask for those that do this, are you using it to discover the bug or to instead fix the bug you already know of?
    - Are you using AI in pull requests such as CodeRabit or Copilot?
      - What is the success rate of these?
  - Generating new code - Generating tests
    - Does this typically come in the case of prompting it and walking away, or as an auto complete suggestion?
  - Simple things - small conversions - Searching or explaining a document
  - Code refactors
    - Is this something you let run and do something else?
    - Are you using git worktrees?
  - — I’d like to as how many people are using Ai to generate side projects, or enhance existing personal code? Are there many doing extra programming outside of work?
- What age is the project
  - Another super interesting response. With most survey responses leaning to new projects, do we think this has an impact on how effective an AI agent can be?
  - For those with longer running projects can you speak to the effectiveness of AI agents in your code base?
  - From my experience looking through possibly not well honed or “sharpened” code, it has caused the Ai to struggle further than it would have likely needed to.
- Project language / framework
  - I sort of expected the JS / TS preference here in Copenhagen, but for those that responded with PHP, Go, Rust, Swift - odin, Elixir/Phoenix
    - Is this a new project or something that has been around for some time?
    - Is this something you are still actively maintaining or replacing?
- AI comprehension in codebase
  - I have found it struggles with newer code examples, of course because training data may be out of date. Then even when I provide it exact docs, or ask it to reference a docs website it will fail to follow them close enough.
  - Any thoughts or ideas on how we can improve this?
  - Is this possibly us not keeping our code “sharp” and so technical debt is the consequence of poor AI readability?
- Productivity (or not)
  - This is my personal favorite question. As personally, currently, I don’t feel any more or less productive. I can work faster for a bit, but then when I hit an AI issue all that time gained slows and is negated.
  - How are those that feel so successful working with it, what challenges have you seen?
  - I’m very happy we had no respondents with they are performing worse with Ai 🙂
- Language Model families
  - Claude, by some margin comes out on top. With the current model selection. I haven’t played with it much, but have heard nothing but positive feedback.
  - For those that don’t think about models, I’m mostly with you. And this is a pain point for me. I don’t want to have to figure out manually or by doing research which model works best for X thing. I want when I prompt for the product to pick for me, or use a model that is just smart enough all on its own.

### Other resources

- Tanner and the host discuss that in development, there is not as much staring at blank files. Also tanner states for job security. For those concerned with job security, if you feel like Ai can generate 100% of the code you write it may be time to continue learning. If you are more at 50% you likely have great job security still.
  [Software Engineering Daily](https://pca.st/episode/044b74b4-285d-42c1-9fe6-021e278bf0eb?t=2666) — TanStack and the Future of Frontend with Tanner Linsley

![qr code linking to - Software Engineering Daily](./image/1.png)

- [How about Tomorrow?](https://pca.st/ibumorp2) — Adam Elmore & Dax Raad (SST & [OpenCode](https://github.com/sst/opencode))
  - There is something interesting about OpenCode, which is they have LSP integrations. They have talked about how this impacts the agent to ensure it is giving you valid and can correct itself. For those using agents, have you ever had an Ai agent generate code that is calling a method that doesn’t exist? This is one of the examples by using the LSP will help to resolve.

![qr code linking to - How about Tomorrow?](./image/2.png)

- [LLMs for web developers with Roy Derks](https://pca.st/4vrcszm5) — PodRocket

![qr code linking to - LLMs for web developers with Roy Derks](./image/3.png)

- [Reimagining the Windows Terminal with Warp's Zach Lloyd](https://pca.st/cnwt4qmb) — Hanselminutes

![qr code linking to - Reimagining the Windows Terminal with Warp's Zach Lloyd](./image/4.png)

### Recap

In lots of the discussions I’ve had, the podcasts and content I’ve listened to the take away has been that Ai can be used as a developer on your behalf. Using things like PRDs, well defined design documents, or acceptance criteria with goals the agent can “check off” will help it behave more like your own personal co-worker and have better results. With the new ways of prompting it has become easier than ever, however I’ve still yet to learn how this is meant to work. This means productivity and learning can extend further. I’m excited for this era of development and seeing where it will take our careers!

### Frequent concern

A common question I’m asking others is the process we are currently doing something we should be paying for, as the providers of the server / code, or is this something that can run on the client? Some examples of this may be mapping over data to re-structure the values to be more meaningful in a client environment. Should we really be paying for server time on this action? Seems like the client can do that. “local first”

- This is my same sentiment when it comes to AI.
  - I have had a strong feeling we will start moving more and more to smaller models for uses in the browser.
  - However haven’t seen this yet, does anyone else share a similar vision?
  - Being able to just call things all on a users device (for devices that are powerful enough)?

### Future hope

I have a vision or hope for the future. Where the browser can ask permission, much like it already does to access your webcam, microphone, or other physical hardware, to tie into your local LLM for given features. The vision hones in that you can set it up in your operating system as a “feature” exposable to other tools. This means **YOU** are in control of what model you use, if it is local or remote, and if it is even enabled at all. By running on your OS level it means it can be more performant than what is in the browser and just simply connect through a web socket or some other simple type of connection.

Just think being able to go to a recipe website, and passing that to a local LLM, no payment to other services just your own electricity and time, then getting it summarized and or even translated to your language or measurement system, classic USA problems.

~~IE summarization of text, translations, simplifications, ect. Then you can control which model is used and where it's used (locally or remotely). In this way we are also not limited by web technology. We would rely on a socket connection to interface with the LLM locally (run by your OS) and can give the results quicker as it is likely running in a more performant manner.~~
