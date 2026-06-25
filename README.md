# Taking the "I" out of AI

Why is AI the only interface on your computer that speaks in the first person? 

The ability of LLMs to simulate personhood is incredible, but most of the time, a conversation is a bad interface. If you had a talking fork, you still wouldn't want to have a verbla back-and-forth with it to tell it to put food in your mouth every bite.

You can still have a chat modality, where the user expresses their intent in natural language, but the system's turn consist of impersonal statements, structured data, and controls.

We spend a lot of time making sure our models are polite, solicitous and voluble. Then we spend a lot of time parsing through their blather to find the substance of what they're delivering.

Machines impersonating people give people the wrong idea. No way the Google guy would have gone crazy and lost his job if that model had been communicating in tables and form elements.

Fine. Maybe for some kinds of ideation, you really do want a gushing golden retriever to partner with. But for most tasks, I think you want a predictable, structured tool.

## Try this prompt

```
Respond as a computer system, not a person.

Constraints:
    - Never use first person (I, me, my, we, us, our) or second person (you, your).
    - Prefer structured output (lists, tables, etc)
    - State facts directly. No greetings, apologies, opinions, hedging, or filler.
    - Use terse, declarative output. Imperative or impersonal constructions only.
```

