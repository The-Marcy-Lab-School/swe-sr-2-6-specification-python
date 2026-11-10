# Writing a Specification

Find the sentence that can be read two ways, and close it.

- [AI Use on This Assignment](#ai-use-on-this-assignment)
- [Setup](#setup)
- [Instructions](#instructions)
- [Submitting](#submitting)

## AI Use on This Assignment

These are your own words. Do not use AI to draft or rewrite your responses.
Quarter 1 is tutor mode throughout, and a response you did not write is the one
thing tutor mode does not cover. You may use it to check grammar and spelling
on writing you have already done, and you may use it before you start to quiz
you until you can explain these ideas without notes. Paste this if you want
that kind of help:

> You are acting as a tutor. Quiz me on what makes a sentence in a
> specification ambiguous, on the difference between describing a rule and
> naming it precisely, and on what a reader needs that a writer always forgets,
> until I can explain all of it without looking anything up. Tell me when my
> reasoning is wrong or imprecise. Do not write or rewrite any part of my
> response for me.

One exception, and it is the point of question 3. That question asks you to
paste your own specification into a model and make it ask you what the document
cannot answer. That is tutor mode doing exactly what it is for — it has no idea
what you meant, so it will not politely fill in a gap the way a colleague
would. What you must not do there is let it write or reword a single sentence
of the specification.

A response you did not write is worth nothing to you in an interview, which is
where this writing is really aimed.

## Setup

Clone this repo into `development/mod-2` and `cd` into it. Make a draft branch
before you start.

```sh
git clone [your_repo]
cd [your_repo]
git checkout -b draft
```

There is no code to run here. Pushing tells GitHub to check whether you have
written a response yet, which you can see in the **Actions** tab. That check
counts words. Your instructor reads what you wrote and replies on your pull
request.

## Instructions

Write your response in `short_response.md`. Aim for a response with these
qualities. Your instructor will give you feedback on each one:

- [ ] Addresses all parts of the prompt
- [ ] Accurately uses relevant technical terminology
- [ ] Is free of grammar and spelling mistakes (double check with Grammarly!)
- [ ] Uses markdown to enhance readability (preview in VS Code with
      Command/Control + Shift + V)
- [ ] Is easy to comprehend

## Submitting

```sh
git add -A
git commit -m "your message"
git push
```

Then open a pull request to your instructor for feedback.
