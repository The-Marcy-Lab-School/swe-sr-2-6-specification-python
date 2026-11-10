# Short Responses

For this short response assignment, aim to write a response with the following
qualities (your instructor will give you feedback on these areas):

- [ ] Addresses all parts of the prompt
- [ ] Accurately uses relevant technical terminology
- [ ] Is free of grammar and spelling mistakes (double check with Grammarly!)
- [ ] Uses markdown to enhance readability (preview in VS Code with
      Command/Control + Shift + V)
- [ ] Is easy to comprehend

Write your response in the space provided. Make sure to preview your markdown
to check how it is rendered before submitting.

**Answer these in order.** Unlike most short response assignments, these three
build on each other: question 2 asks you to write a specification, and question
3 asks you to find the holes in the one you just wrote. Doing 3 without 2 is
not possible.

## Question 1

Here is a specification for a laundrette booking system. It was written by
somebody who understood their own system perfectly.

> **Machine.** Each machine has a number and a size. A machine can be booked by
> one member at a time. Large machines cost more.
>
> **Booking.** A booking records the member, the machine and the slot. Bookings
> can be cancelled if they have not started. A member cannot hold too many
> bookings at once.
>
> **Laundrette.** The laundrette holds the machines and the bookings. When a
> member books a machine, the laundrette checks the machine is free and that the
> member is allowed another booking. A cancelled booking frees the machine.

Every sentence here is confident and several are useless.

**First**, find **four** sentences a reader could satisfy in more than one way.
For each one:

1. Quote it.
2. Give **two different implementations** that both honestly satisfy it, and
   that disagree. Not two readings — two pieces of behavior a reviewer would
   accept.
3. Rewrite the sentence so only one remains.

**Second**, name **one thing missing entirely** — not vague, absent. A rule or
relationship the system obviously needs that no sentence mentions. Write the
sentence that should be there.

**Third**, answer this. Every ambiguous sentence above is ambiguous in roughly
the same way: it names a rule without naming the **value or condition** the rule
turns on. Say why a writer does not notice this about their own document, in one
or two sentences.

That last part is the whole reason this question exists, and it applies to the
specification you are about to write for your project.

### Your Response

[Write your response here]

## Question 2

This is practice on **someone else's system**, deliberately. Your own system's
specification is `DESIGN.md`, and it is the project's work, not this
assignment's.

Here is the brief, from the same laundrette:

> Members book washing machines by the half-hour slot. A member may hold two
> bookings at a time, and cannot book a slot that has already started. Machines
> come in two sizes and the large ones cost double. A machine out of order takes
> no bookings until an engineer clears it. Staff need to see who is booked on
> what today.

Write the specification for **one class only: `Laundrette`**, the coordinator.

It has to cover, in prose a developer could build from without asking you a
question:

- **What it owns.** Every collection, and whether other code can reach it.
- **Every method.** For each one: what it takes, what it returns, and what it
  **refuses** and with what error.
- **Every rule it enforces**, with the exact value or condition the rule turns
  on.
- **Its relationships** to the other classes, and which direction each points.

Then, below the specification, answer two things:

1. **Name one decision the brief did not make for you.** You had to choose, the
   brief is silent, and a different reader would have chosen otherwise. Say what
   you chose and why.
2. **Name the method you found hardest to specify**, and say what made it hard.

A specification is not a description of code you have already written. It is the
document that comes first, which is why "it checks the member is allowed another
booking" is not good enough: a developer cannot build a check without knowing
what *allowed* means.

### Your Response

[Write your response here]

## Question 3

A specification is finished when a competent reader has no questions left. You
cannot be that reader for your own document, because you know what you meant.

Take the `Laundrette` specification you wrote in the previous question, paste it
into an AI model, and ask it to find what it cannot answer. This prompt works:

> You are reviewing a specification I wrote. Do not write any part of it, and do
> not suggest wording. Your only job is to ask me questions that the document
> cannot answer — places where you would have to guess to build this. Ask one
> question at a time and tell me what you would have had to assume.

**Tutor mode only.** Asking it what your document is missing is tutor mode.
Asking it to fix your document is not, and a specification you did not write is
worth nothing when a reviewer asks you to defend it.

Hand in three things:

**First**, **three questions it asked that your document could not answer.**
Quote them. If the first three were trivial, keep going until three are real —
a question is real when you had to make a decision to answer it.

**Second**, for each question, the **sentence you added or rewrote** to close it.
Show the before and the after where you changed something.

**Third**, answer this: of the three, how many were things you knew and had not
written down, against things you had not decided at all? Say which, and say what
that tells you about reading your own work.

A model is useful here for one specific reason: it has no idea what you meant,
and it will not politely fill in a gap the way a colleague would.

### Your Response

[Write your response here]

