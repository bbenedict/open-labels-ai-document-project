This article was originally posted on LinkedIn.  AI was later asked to add some details not covered in the original article. This is a good example of how we can indicate when AI is used on something primarily written by a human.

# Are you using AI local-first or remote-first?

I was wondering how many AI-forward developers are using AI local-first or remote-first. The core difference is where your feature branch lives 🛖 during active development.  Local-first remains the more established approach for AI-assisted development, while remote-first is gaining traction for autonomous coding agents, parallel execution, and team collaboration, with no clear consensus yet on which is better. [AG-SE]

For personal projects, I use Cursor operating on a local feature branch. Claude seems to have been initially designed to work this way. Claude told me himself 💬

> "Claude Code is designed and documented, yes — local-first via the CLI is the primary/native mode, and GitHub.com-first is more of an edge case or specialized setup."

My new company is remote-first. Branches are created in the cloud ☁️ and pushed to staging or production from there.

Remote-first has nice benefits including:

- ✅ Work in progress is more visible
- ✅ Collaboration is easier as all developers can update the remote branch
- ✅ Virtual environments enable collaborative hands-on testing

Local-first on the other hand:

- ✅ Easier for HITL coding when needed or desired
- ✅ You can use local tools and techniques like you always have
- ✅ Virtual environments are not required

There are tradeoffs beyond where the code lives. Local-first development gives developers direct control over their environments and tools, while remote-first development can provide greater consistency, shared infrastructure, and easier access to work in progress. The choice can also affect development costs, security, and how easily teams coordinate multiple AI coding agents. [AG-PA]

The two approaches aren't necessarily mutually exclusive. A team might use local development for interactive coding and debugging while relying on cloud environments for automated agents, testing, and deployment. As AI coding agents become more capable, the question may be less about choosing one approach and more about deciding which activities belong in each environment. [AG-PA]

I am adjusting nicely to a remote-first approach and was wondering how many of you are doing the same ❓ Would be great to get some data on this.

This document uses the Open Labels AI Document Project (OLADP) standard to disclose how AI contributed to document creation. You'll see labels such as [AG-TC] that indicates a table or chart (TC) was AI generated (AG). Learn more about the standard and how it benefits the document reader at [Open Labels AI Document Project](https://github.com/bbenedict/open-labels-ai-document-project)
