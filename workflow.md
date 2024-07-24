# An Iterative Cycle For GPT Prompt Engineering 

I've chosen to describe this workflow as the "iterative cycle for GPT prompt engineering" although other names would be just as accurate. You might wish to call this the "virtuous cycle of GPT prompt engineering" or something similar. It doesn't matter.

## Prompt Production, Prompt Production

The 'gist' of this workflow is as follows:

Instead of adopting a trial-and-error approach to GPT prompt engineering (by which we test a prompt, assess its output, and attempt to iteratively improve it while running the prompt afresh each time) we spend the majority of our time and effort on the prompt refinement part of the process. 

We create a custom GPT whose sole purpose is to analyse prompts as we develop them and refine them. 

This GPT needs to have several key qualities:

- As foundational knowledge, it needs to understand the limitations and capabalities of the target LLM and GPT
- This foundational knowledge needs to be dynamic. That is to say: as the capabilities of the GPT mature and evolve, its knowledge must update in tandem. 

Developing a custom GPT for the sole purpose of prompt engineering is akin to "baking in" prompt engineering awareness to the GPT. 

For those using GPTs programatically (via an API) this also allows us to optimise our spend by negating the necessity of re-running draft versions of the actual prompt, generating unused output with each generation.

Next, we need a very simple folder structure for working on prompts. We could use a Git-based system for version control (like Github). Or we could store each iteration of the prompt as a discreet markdown file. For the purpose of visibility, the latter approach is favored here. 

## How To Use The Approach

In simple steps:

1: Develop your prompt engineering GPT. 
2: Build out a folder structure for storing your prompts as you iterative through the prompt engineering/drafting/optimisation process (with or without collaborators)
3: When your prompts are "production ready" commit them to a prompt libary. As above, this can be a shared resource or a private one. 


 