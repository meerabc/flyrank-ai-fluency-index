# Retrospective

Written for the person I was in Week 1.

## What I set out to do

Going into this track, I thought AI Fluency was mostly going to be about
prompting better, learning the right phrasing, the right tricks, so ChatGPT
or Claude gave me better answers faster. I expected a portfolio site at
the end, some assignments about audits and workflows, and a personal
agent I'd probably build as a Claude Project since that felt like the
obvious, low-effort path. I did not expect to end up writing real Node.js
code, debugging a broken npm package's API, or arguing with myself over
whether a summary was too vague to trust.

## What actually changed

The single biggest shift was learning to treat AI as a genuine
collaborator instead of a question box. Early on, my instinct was still
to ask a question, get an answer, move on. By the time I was building the
study agent, the actual work looked different: propose a design decision,
have it pushed back on, defend it or change my mind, watch the result,
and go again. The Claude API versus Gemini decision is a small but real
example, I had assumed Claude API the whole way through my FL-06 spec,
and it took an actual check to realize it wasn't free and conflicted with
the program's own rules. That kind of catch only happens when you're
genuinely working something through together, not just accepting the
first answer.

The second real shift was watching what "iteration" actually looks like
outside of a course description. My FL-07 build log has three real bugs
in it: a library API that had quietly changed versions, a duplication bug
in how PPTX slides were being parsed, and a malformed image payload that
flooded my terminal with an unreadable error. None of these were
hypothetical "here's what could go wrong" examples, they were things that
broke, got diagnosed from real evidence, and got fixed. I used to think
of debugging as something you do when you're bad at the thing. Now I
think of it as just what building looks like.

The third thing, and the one I didn't expect at all, was how much
judgment mattered more than generation. When my agent's summary of a
slide was technically correct but too vague, the fix wasn't "ask AI to
try again," it was deciding, specifically, what "good enough" meant for
this agent's actual job, then rewriting the instruction to demand it.
That's not a prompting trick. That's the same kind of decision-making
this whole track kept coming back to: choose the claim, choose the
audience, choose what a case study proves, choose what a good summary
actually contains.

## What I'd build next

The obvious next step is expanding the study agent past PPTX and PDF,
since real coursework doesn't stay in two formats, and testing it against
subjects further from what I've already validated. I'd also want to
build a lighter feedback loop into the weak-spot tracking, right now it
only knows what I self-report, and a smarter agent would find ways to
verify understanding more directly instead of trusting my honesty alone.

## The three most transferable things

First, real iteration is messy and that's normal, not a sign something's
wrong. Second, working with AI well means pushing back and being pushed
back on, not just prompting harder. Third, judgment, deciding what
"correct enough" or "specific enough" actually means for a given task, is
the actual skill underneath everything else in this track, prompting
included.
