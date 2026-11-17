# TeamFlow — Day 3

## Step 2 — Think of Solutions: Identity

### The Design Question

What does "a person being known and identified" mean in the simplest system?

### My First Answer

Name, mobile number, email.

### What Was Wrong

1. These can all change. If owner points to them, changing them breaks the link.
2. I did not ask which one is unique.
3. I skipped the purpose: owner and history must point to one person, reliably, forever.

### The Decision

**Every person gets a unique internal ID that never changes. Name and email are labels for persons. Owner and history always point to the ID, never to name or email.**

### Why It Matters

Email can change. If owner points to email, changing it breaks every task that person owns. An internal ID never changes, so owner and history stay intact.