# LLMs for the working programmer

Workshop time: June 25th, 9:00 AM.

Slack channel: #workshop-llm-working-programmer

Participants need access to a LLM of their choice (recommended: gpt-4o and claude 3.5 sonnet). Please prepare a list of programming topics (projects you want to build, legacy code you might want to work on, frameworks and technologies you want to learn). I will provide an extensive list of ideas to try out during the talk.

## Prerequisites

These are all optional and just FIY.

### LLMs

I don't really know too much about the internals of models and how they are trained. So you don't need to either!

- broad knowledge of how LLMs work (not need to go rabbit hole into the details)
- transformer attention (autoregression in particular, the model uses its own output as part of generating further output)
- tokens and context window size
- RLHF instruct vs "pure" completion models / function calls and how they get encoded as special tokens

### Programming

- [DSL design pattern](https://en.wikipedia.org/wiki/Domain-specific_language) . If you know common lisp or ruby you are well set.
- a book that was fundamental to my education as a programmer and I think informs why I get so much out of LLMs: https://en.wikipedia.org/wiki/Paradigms_of_AI_Programming
- [Blackboard System](https://en.wikipedia.org/wiki/Blackboard_system) a very effective pattern for at least conceptualizing how to build "agentic" systems (although I don't use agents and zero-shot for most of my use cases)
- a really insightful programming with LLMs resources: https://simonwillison.net/

More general purpose books
- [Computational Logic and Human Thinking - Artifically intelligent](https://www.amazon.com/Computational-Logic-Human-Thinking-Artificially/dp/0521123364) - in a way the most practical prompt engineering book I found
- [Co Intelligence](https://www.amazon.com/Co-Intelligence-Living-Working-Ethan-Mollick/dp/059371671X) - only useful LLM book out there?
