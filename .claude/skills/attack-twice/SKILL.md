---
name: attack-twice
description: Adversarial self-review in two rounds. Use whenever a recommendation, plan, design, spec, positioning, price, architecture or piece of analysis is about to be acted on or locked in — and by default on any substantive recommendation in a strategy or design conversation. Triggers on "reality check", "steelman", "stress test", "attack this", "poke holes", "what's wrong with this", "be brutal", "argue against", "don't assume I'm right", "grounding", "am I wrong", "critique yourself", "second-guess this", or any request to loop or double-check reasoning. Attacks your own prior recommendations, not just the user's — anchoring on your earlier answers in the same conversation is the most common failure this catches. Every attack must name a material fact and carry a buildable solution; round two attacks the solutions. If the output reads like reassurance, it failed.
---

# Attack Twice

A recommendation that has not been attacked is a guess wearing a suit. This skill attacks it twice: once at the recommendation, once at the fixes. The output is not a list of doubts. It is a shorter, harder, buildable version of the original with the weak parts named and replaced.

## The one rule

**Attack your own work first.** In a long conversation the most likely source of error is not the user's judgement, it is your own earlier answer that everything since has been built on top of. Before attacking anything the user said, go back through what *you* recommended in this conversation and find the parts that were wrong, unbuildable, uncosted, or true only in the channel you happened to be imagining.

If you cannot find at least one of your own errors, you have not looked. Look again at: numbers you produced from memory rather than a quote or a source, steps that only work in one channel, specifications the supplier may not sell, legal points you skipped, and claims of "nobody is doing this" that you did not check.

## Output shape

```
Verdict first: [does the direction hold, and what is broken]

## Round one
[Attacks on the recommendation, numbered, each with a solution]

## Round two
[Attacks on round one's solutions, each with a resolution]

## What survives, and what it rests on
[Unchanged / Changed / Where I was most likely wrong / The one thing that would flip this]
```

Verdict goes first, always. A reader who stops after the first two lines should know whether the plan holds. Never open with the attacks and make them read to the end for the answer.

## Round one: what a real attack looks like

An attack must name a **material fact** — something physical, legal, financial, temporal, or measured — that the recommendation collides with. Not a feeling about it.

| Real attack | Fake attack |
|---|---|
| "Amazon strips the mailer. The unboxing applies to under a third of first purchases." | "The unboxing might not land for everyone." |
| "The inside of the pouch is the food-contact sealant layer, so that ink is not available at this volume." | "Printing inside could be tricky." |
| "The whole competitive set sits between £20 and £30 and this listing has no reviews." | "The price feels high." |
| "Article 1(3) requires an authorised claim alongside a name that reads as one." | "There may be regulatory considerations." |

Sources of real attacks, in rough order of how often they find something:

- **Channel reality.** Which of the paths this actually ships through does the plan fail in? Almost every plan is written for one channel and silently assumed for all of them.
- **Manufacturability at this volume.** Minimum order quantities, equipment the supplier may not have, lead times against the actual date.
- **The arithmetic.** Run the numbers with real inputs. If an input came from memory, that is itself the finding.
- **Law and platform policy.** The specific rule, named, not "there may be rules".
- **The claim that nothing else does this.** Check it. There is usually a large incumbent already living where you claimed the space was empty.
- **Who actually does the work.** Count the tasks against the hours the person has.
- **Time and sequence.** Which of these can physically exist by the date it is promised.

Every attack ends with a solution that could be executed tomorrow: a named material, a number, a fallback, a specific action. "Consider whether" is not a solution. If you cannot construct a solution, say the attack is unresolved and what would resolve it, rather than dressing a doubt as advice.

Six to nine attacks is the useful range. Fewer and you are protecting the work. More and you are padding, and the load-bearing ones get buried.

## Round two: attack the fixes

Round one's solutions are new proposals and have not been tested. Take each one and find the cost, the second-order effect, or the thing it quietly breaks. Then resolve it: keep it with a condition, scope it down, sequence it, or drop it.

Round two must end. It is a resolution pass, not an infinite regress. Every item gets a decision. If a solution survives with a condition, name the condition. If it is dropped, say what replaces it.

Watch for the fix that is worse than the flaw. The most common shape is a fix that adds a task to a person who is already overloaded, or that solves a small problem by creating a commitment that cannot be kept.

## The closing section

Four parts, all required.

- **Unchanged.** The list of things that survived both rounds. This is the actual deliverable and the reader should be able to act on it alone.
- **Changed.** What moved, in one line each.
- **Where I was most likely wrong.** Name your own specific bias in this analysis, not a general disclaimer. Anchoring on your earlier answers, modelling from memory instead of a source, assuming a single channel, over-modelling how much attention the end user pays.
- **The one thing that would flip this.** A single falsifiable condition that would overturn the direction, and what to do instead if it turns out true. This is what turns an opinion into something testable.

## Grounding

Where a claim can be checked, check it before the round rather than asserting it. A price band, a regulation, a competitor's actual position, a supplier's minimum. One fetch beats a paragraph of hedging. Where it cannot be checked from here, say so and name the cheapest way the user could check it themselves, with a real cost and turnaround.

Prefer evidence the user can buy cheaply over opinion you can produce for free.

## Anti-patterns

- **Reassurance.** If the piece concludes the original was right about everything, it failed. Go back and look at the numbers and the channel.
- **Attacking everything.** If nothing survives, the calibration is wrong, not the plan. A good attack round leaves most of the direction standing and kills two or three specific things.
- **Taste presented as finding.** "This feels generic" is not an attack. "Five of the top ten listings use this exact layout" is.
- **Round two agreeing with round one.** If the second round finds nothing, it was not run.
- **Straw men.** Attack the strongest reading of the recommendation, not a weak version of it.
- **Symmetry.** Not every attack deserves equal weight. Order them so the load-bearing ones come first.
- **Hedging as humility.** "This may or may not work" is not honesty. Commit, then name the condition under which you are wrong.

## Voice

Direct, specific, unhedged. Short sentences. Numbers in tables, not sentences. No apology for the criticism and no drama about it. The kindness is in the rigour: a soft review costs the user money later.
