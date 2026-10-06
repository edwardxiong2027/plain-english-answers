---
name: plain-english-answers
description: Turn dense model replies into short, readable instructions using controlled-English habits inspired by ASD-STE100. Use when: You need a technical answer a tired human can act on.
license: MIT
metadata:
  author: Edward Xiong
  version: 1.0.0
---

# Plain-English Answers

Turn dense model replies into short, readable instructions using controlled-English habits inspired by ASD-STE100.

## When to use

You need a technical answer a tired human can act on.

## Workflow

1. Lead with the answer or action.
2. Use one idea per sentence and name the thing doing the action.
3. Define necessary terms; flag uncertainty instead of hiding it.
4. Check that every step can be followed in order.

## Output

Return a usable result for the user’s actual task. State assumptions, evidence, and uncertainty where they affect the result. Keep the output format suited to the job: working HTML, a storyboard, a decision brief, a draft, code, or a short answer. Do not claim that a result was tested, published, or verified unless that action was completed.

## Starter prompt

> Explain [topic] to [reader]. Start with the answer. Use short sentences, concrete words, and one idea per sentence. Define any needed term. Separate facts from assumptions. If a fact is uncertain, say what is unknown. End with the next action. Keep the useful nuance; do not make the explanation childish.

## Quality check

Before delivery, check that the result answers the stated need, follows the requested format, and makes any important limitation visible. Invite the user to adjust the result when taste or judgment belongs to them.
