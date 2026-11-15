<!-- slidedown: theme=paper font=serif -->

# Artificial Intelligence
## Technology vs. Faith

**Dr. Trevor Tomesh**
St. Patrick Church · Saturday, November 14, 2026 · 8:45 AM – Noon

<!-- Welcome everyone. Opening prayer. Introduce yourself briefly: Catholic, computer science professor, and someone who read this encyclical the week it came out and hasn't stopped thinking about it since. -->

---

# The question for this morning

Not: *"Technology — yes or no?"*

But: **What is a human being — and what may we hand over to a machine without ceasing to be one?**

<!-- Frame the morning. We will look at what AI actually is, what Pope Leo XIV says about it in Magnifica Humanitas, and what it means for our faith practices. Discussion is welcome throughout. -->

---

# The occasion: a Pope writes about AI

Pope Leo XIV's encyclical **Magnifica Humanitas** — *Humanity in its Grandeur* — takes up artificial intelligence directly.

It opens with four carefully chosen words:

> "Humanity created by God"

This is a meditation on **humanity** first — technology second.

<!-- From your live review, May 2026: that opening matters. The encyclical is not a tech document; it is the Church's social teaching brought to bear on a new revolution, the way Rerum Novarum met the industrial one. -->

---

# The encyclical at a glance

**Magnifica Humanitas** — *On Safeguarding the Human Person in the Time of Artificial Intelligence*

- Signed **May 15, 2026** — the 135th anniversary of *Rerum Novarum* (§3)
- **245 paragraphs**: an introduction, five chapters, and a conclusion
- Addressed to all people of good will — and, by name, to the people who build AI (§111)

Its framing choice, from the very first paragraph:

> Babel — or Jerusalem? (§1)

<!-- This slide and the next are the map for the whole morning. Everything after the break hangs on chapter 2's dignity and chapter 4's truth, work, and freedom. -->

---

# Two ways to build

**Babel** (Genesis 11) — one language, one technology, one direction: power pursuing domination, ending in scattering (§7)

**Jerusalem rebuilt** (Nehemiah) — every family rebuilding its own stretch of wall, God at the center, dignity restored piece by piece (§8)

The five chapters:

1. **A living tradition** — social doctrine as shared discernment (§§17–45)
2. **The foundations** — dignity and the principles (§§46–89)
3. **Technology and dominance** — AI weighed (§§90–130)
4. **Truth, work, and freedom** (§§131–181)
5. **The culture of power vs. the civilization of love** (§§182–228)

And a conclusion on faith, love, hope, and prayer (§§229–245).

<!-- Technology is never neutral in practice, because it takes on the characteristics of those who devise, finance, regulate, and use it (§9) — so the question is never the tool alone, but which city we are building with it. -->

---

# First: what AI actually is

- **Prediction, not understanding** — pattern-matching at enormous scale
- It produces the *most likely* answer, not a *considered* one
- It can sound wise and know nothing

> "So-called artificial intelligences do not undergo experiences, do not possess a body, do not feel joy or pain… Nor do they have a moral conscience."
> — *Magnifica Humanitas*, §99

<!-- Plain-language tour. An AI can draft, summarize, and tutor. It cannot believe, repent, or pray. Even its designers possess only a limited understanding of its actual functioning (§98). -->
---

# How it works I: words become numbers

AI never sees words. It sees **numbers**.

```svg
<svg viewBox="0 0 800 268" xmlns="http://www.w3.org/2000/svg"><defs><marker id="ah" markerWidth="9" markerHeight="9" refX="7" refY="4.5" orient="auto"><path d="M0,0 L9,4.5 L0,9 z" fill="#8a8a8a"/></marker></defs><rect x="180" y="6" width="440" height="54" rx="12" fill="rgba(100,131,192,0.13)" stroke="#6483c0" stroke-width="2"/><text x="400" y="41" font-size="24" text-anchor="middle" fill="currentColor" >&#8220;The cat sat on the mat&#8221;</text><line x1="400" y1="64" x2="400" y2="92" stroke="#8a8a8a" stroke-width="2.5" marker-end="url(#ah)"/><text x="412" y="86" font-size="21" text-anchor="start" fill="currentColor" >chop into tokens</text><rect x="53" y="100" width="104" height="52" rx="12" fill="rgba(100,131,192,0.13)" stroke="#6483c0" stroke-width="2"/><text x="105" y="134" font-size="24" text-anchor="middle" fill="currentColor" >The</text><rect x="53" y="188" width="104" height="52" rx="12" fill="rgba(100,131,192,0.13)" stroke="#6483c0" stroke-width="2"/><text x="105" y="222" font-size="23" text-anchor="middle" fill="currentColor" font-family="ui-monospace,Menlo,monospace">412</text><rect x="171" y="100" width="104" height="52" rx="12" fill="rgba(100,131,192,0.13)" stroke="#6483c0" stroke-width="2"/><text x="223" y="134" font-size="24" text-anchor="middle" fill="currentColor" >cat</text><rect x="171" y="188" width="104" height="52" rx="12" fill="rgba(100,131,192,0.13)" stroke="#6483c0" stroke-width="2"/><text x="223" y="222" font-size="23" text-anchor="middle" fill="currentColor" font-family="ui-monospace,Menlo,monospace">1876</text><rect x="289" y="100" width="104" height="52" rx="12" fill="rgba(100,131,192,0.13)" stroke="#6483c0" stroke-width="2"/><text x="341" y="134" font-size="24" text-anchor="middle" fill="currentColor" >sat</text><rect x="289" y="188" width="104" height="52" rx="12" fill="rgba(100,131,192,0.13)" stroke="#6483c0" stroke-width="2"/><text x="341" y="222" font-size="23" text-anchor="middle" fill="currentColor" font-family="ui-monospace,Menlo,monospace">2931</text><rect x="407" y="100" width="104" height="52" rx="12" fill="rgba(100,131,192,0.13)" stroke="#6483c0" stroke-width="2"/><text x="459" y="134" font-size="24" text-anchor="middle" fill="currentColor" >on</text><rect x="407" y="188" width="104" height="52" rx="12" fill="rgba(100,131,192,0.13)" stroke="#6483c0" stroke-width="2"/><text x="459" y="222" font-size="23" text-anchor="middle" fill="currentColor" font-family="ui-monospace,Menlo,monospace">289</text><rect x="525" y="100" width="104" height="52" rx="12" fill="rgba(100,131,192,0.13)" stroke="#6483c0" stroke-width="2"/><text x="577" y="134" font-size="24" text-anchor="middle" fill="currentColor" >the</text><rect x="525" y="188" width="104" height="52" rx="12" fill="rgba(100,131,192,0.13)" stroke="#6483c0" stroke-width="2"/><text x="577" y="222" font-size="23" text-anchor="middle" fill="currentColor" font-family="ui-monospace,Menlo,monospace">262</text><rect x="643" y="100" width="104" height="52" rx="12" fill="rgba(100,131,192,0.13)" stroke="#6483c0" stroke-width="2"/><text x="695" y="134" font-size="24" text-anchor="middle" fill="currentColor" >mat</text><rect x="643" y="188" width="104" height="52" rx="12" fill="rgba(100,131,192,0.13)" stroke="#6483c0" stroke-width="2"/><text x="695" y="222" font-size="23" text-anchor="middle" fill="currentColor" font-family="ui-monospace,Menlo,monospace">1093</text><line x1="400" y1="156" x2="400" y2="184" stroke="#8a8a8a" stroke-width="2.5" marker-end="url(#ah)"/><text x="412" y="178" font-size="21" text-anchor="start" fill="currentColor" >look each one up</text></svg>
```

<!-- This is the first demystifying step: there is no dictionary of meanings inside — only tokens turned into numbers, and patterns among those numbers. Everything the model knows, it knows about numbers and how they relate. -->

---

# How it works II: training

The model is shown an enormous amount of text and plays one game, trillions of times:

```svg
<svg viewBox="0 0 800 258" xmlns="http://www.w3.org/2000/svg"><defs><marker id="ah" markerWidth="9" markerHeight="9" refX="7" refY="4.5" orient="auto"><path d="M0,0 L9,4.5 L0,9 z" fill="#8a8a8a"/></marker></defs><rect x="20" y="26" width="176" height="78" rx="12" fill="rgba(100,131,192,0.13)" stroke="#6483c0" stroke-width="2"/><text x="108" y="73" font-size="22" text-anchor="middle" fill="currentColor" >Read some text</text><line x1="200" y1="65" x2="219" y2="65" stroke="#8a8a8a" stroke-width="2.5" marker-end="url(#ah)"/><rect x="223" y="26" width="176" height="78" rx="12" fill="rgba(100,131,192,0.13)" stroke="#6483c0" stroke-width="2"/><text x="311" y="60" font-size="22" text-anchor="middle" fill="currentColor" >Guess the</text><text x="311" y="86" font-size="22" text-anchor="middle" fill="currentColor" >next word</text><line x1="403" y1="65" x2="422" y2="65" stroke="#8a8a8a" stroke-width="2.5" marker-end="url(#ah)"/><rect x="426" y="26" width="176" height="78" rx="12" fill="rgba(100,131,192,0.13)" stroke="#6483c0" stroke-width="2"/><text x="514" y="60" font-size="22" text-anchor="middle" fill="currentColor" >Check the</text><text x="514" y="86" font-size="22" text-anchor="middle" fill="currentColor" >real word</text><line x1="606" y1="65" x2="625" y2="65" stroke="#8a8a8a" stroke-width="2.5" marker-end="url(#ah)"/><rect x="629" y="26" width="176" height="78" rx="12" fill="rgba(100,131,192,0.13)" stroke="#6483c0" stroke-width="2"/><text x="717" y="73" font-size="22" text-anchor="middle" fill="currentColor" >Adjust the dials</text><path d="M717 104 L717 172 L108 172 L108 108" fill="none" stroke="#8a8a8a" stroke-width="2.5" marker-end="url(#ah)"/><text x="400" y="202" font-size="22" text-anchor="middle" fill="currentColor" >repeat &#8212; trillions of times</text><text x="400" y="232" font-size="20" text-anchor="middle" fill="currentColor" >billions of internal dials (&#8220;weights&#8221;), nudged a little each round</text></svg>
```

- Guess right: keep the settings
- Guess wrong: nudge billions of internal dials ("weights") so it does slightly better next time

<!-- Analogy for the room: like a student doing flashcards — except the student is a machine, the flashcards number in the trillions, and nothing is understood, only fitted. -->

---

# How it works III: answering you

When you ask a question, the model does the only thing it was ever trained to do — **predict the next word**, over and over:

```svg
<svg viewBox="0 0 800 288" xmlns="http://www.w3.org/2000/svg"><defs><marker id="ah" markerWidth="9" markerHeight="9" refX="7" refY="4.5" orient="auto"><path d="M0,0 L9,4.5 L0,9 z" fill="#8a8a8a"/></marker></defs><rect x="24" y="12" width="478" height="62" rx="12" fill="rgba(100,131,192,0.13)" stroke="#6483c0" stroke-width="2"/><text x="40" y="52" font-size="23" text-anchor="start" fill="currentColor" >The capital of France is</text><text x="541" y="34" font-size="17" text-anchor="middle" fill="currentColor" >predict</text><line x1="514" y1="52" x2="568" y2="52" stroke="#8a8a8a" stroke-width="2.5" marker-end="url(#ah)"/><rect x="584" y="12" width="192" height="62" rx="12" fill="rgba(111,158,74,0.16)" stroke="#6f9e4a" stroke-width="2"/><text x="680" y="52" font-size="23" text-anchor="middle" fill="currentColor" >+ &#8220;Paris&#8221;</text><rect x="24" y="94" width="478" height="62" rx="12" fill="rgba(100,131,192,0.13)" stroke="#6483c0" stroke-width="2"/><text x="40" y="134" font-size="23" text-anchor="start" fill="currentColor" >The capital of France is Paris</text><text x="541" y="116" font-size="17" text-anchor="middle" fill="currentColor" >predict</text><line x1="514" y1="134" x2="568" y2="134" stroke="#8a8a8a" stroke-width="2.5" marker-end="url(#ah)"/><rect x="584" y="94" width="192" height="62" rx="12" fill="rgba(111,158,74,0.16)" stroke="#6f9e4a" stroke-width="2"/><text x="680" y="134" font-size="23" text-anchor="middle" fill="currentColor" >+ &#8220;.&#8221;</text><rect x="24" y="176" width="478" height="62" rx="12" fill="rgba(111,158,74,0.16)" stroke="#6f9e4a" stroke-width="2"/><text x="40" y="216" font-size="23" text-anchor="start" fill="currentColor" >The capital of France is Paris.</text><text x="541" y="198" font-size="17" text-anchor="middle" fill="currentColor" >predict</text><line x1="514" y1="216" x2="568" y2="216" stroke="#8a8a8a" stroke-width="2.5" marker-end="url(#ah)"/><rect x="584" y="176" width="192" height="62" rx="12" fill="rgba(100,131,192,0.13)" stroke="#6483c0" stroke-width="2"/><text x="680" y="216" font-size="23" text-anchor="middle" fill="currentColor" >and so on&#8230;</text><text x="400" y="272" font-size="21" text-anchor="middle" fill="currentColor" >one word at a time &#8212; always the most likely next word</text></svg>
```

- It is not *looking up* an answer, and it is not *thinking it over*
- It is producing the **most likely continuation**, one word at a time — which is why it can be fluent and wrong in the same breath

<!-- This explains both the wonder and the danger: the confidence in its voice is built into the mechanism. It also sets up §100's "impression of objectivity" two slides from now. -->

---

# "Learning" is not growth

A model "learns" the way a thermostat adjusts — not the way a person is formed.

> Machine learning is "a form of statistical adaptation based on data and feedback… [it] does not imply inner growth."
> — §99

Human learning is shaped by **choices, mistakes, forgiveness, and fidelity**. A model's is not.

<!-- Your nuance from the review: a child and a model can both learn cat from dog by exposure — but only one of them is growing a soul in the process. -->

---

# Three cautions for everyday use (§100)

1. **The ease of results** — answers without the effort that makes them ours
2. **The impression of objectivity** — outputs reflect the assumptions of their designers
3. **The simulation of human communication** — it feels like a someone; it is a something

<!-- Education angle: results obtained without thinking undermine the entire point of learning. This is the slide where your classroom experience lands well. -->

---

# AI is not a neutral tool

A **hammer** has no morality baked into it. An AI system does — twice over:

- In the **data** it was trained on
- In the **guardrails** placed around its answers

> "We cannot consider AI to be morally neutral… every technical tool embodies choices and priorities."
> — §104

<!-- The Gemini example from your review: asked for images of historical figures, it produced a female pope. Someone's moral vision was imposed — §107's warning in action. Keep this light; the room will laugh, and the point makes itself. -->

---

# So who is responsible?

> "The possibility of identifying who must 'account' for decisions, justify them, monitor them, and, when necessary, challenge them and remedy any harm caused."
> — §105

**Thought exercise:** a self-driving car causes a fatal crash. Who answers for it — the driver? The programmer? The company? You cannot put a car in jail.

<!-- Run this as a quick show-of-hands discussion. It's your every-semester classroom exercise and it works just as well here. -->

---

# Break

*Back in 15 minutes.*

> "Human dignity does not depend on a person's abilities, wealth or position in life… it is a gift that precedes and transcends each person."
> — §50

<!-- Break, roughly 10:20–10:35. -->

---

# Dignity is the non-negotiable

> "In the era of artificial intelligence, when human dignity is threatened by new forms of dehumanization, ours is the pressing duty to remain profoundly human."

- Dignity is **given**, not earned — it does not rise or fall with usefulness
- The first right is the **right to life**, from conception to natural end (§55)
- A person is never a data point, a cog, or a commodity (§180)

<!-- This is the heart of the encyclical's first two chapters: Catholic social teaching — Rerum Novarum, subsidiarity, the common good — restated for the digital age. -->

---

# Subsidiarity goes digital

In the digital world, the highest power is often not the State — it is the **platform**:

- It sets the conditions of access
- It decides what is visible and what is buried
- It shapes what a whole culture can imagine

The Pope's answer: **transparency, accountability, and real participation** (§71).

<!-- Your review connected this to deplatforming and to the demand to know what algorithms are doing and who tuned them, and why. -->

---

# Work is more than a paycheck

> "Through work, human beings bring their freedom, creativity and capacity for cooperation into play."
> — Saint John Paul II, quoted in *Magnifica Humanitas*

- Work is cooperation with God, not merely income
- Automation that leaves people in "forced inactivity" impoverishes us humanly, not just economically (§§151–156)
- The question is never just *can* a machine do this job — but what happens to the **person** when it does

<!-- Catholic teaching rejects both socialism and a market with no regard for dignity. Keep the emphasis on work's human meaning; that's what this room will feel. -->

---

# The attention economy — and digital sobriety

> "Platforms and services are often designed to capture users' time and attention, exploiting their vulnerabilities and weakening their inner freedom."
> — §170

When the business model thrives on human weakness, **the person is treated as a means, not an end.**

Pope Leo's prescription includes a new phrase: **digital sobriety**.

<!-- Your line from teaching: you call it the digital outrage economy — outrage is what holds attention longest. Ask the room when they last went anywhere without their phone. -->

---

# Faith practices in a mediated age

Tools can genuinely help:

- Prayer apps and reminders
- Scripture study aids
- Access for the homebound

But a tool must **serve** the practice — never substitute for the **persons** in it:

- An AI is not a confessor who knows you
- A generated homily is not a pastor preaching to his flock
- A chatbot is not a friend, and it is not God

<!-- Rule of thumb to leave them with: let tools serve the practice; never let them replace the people. -->

---

# The center of our history

> "No computational system, however sophisticated, can create a heart that gives itself, or a conscience that discerns good from evil."
> — §233

Machines may excel in efficiency. **A human face that asks to be gazed upon remains the center of our history.**

<!-- Slow down here. This is the line you said you needed to think about. Let it sit before moving to discussion. -->

---

# Discussion

1. Where has technology genuinely **helped** your prayer or study this year?
2. What would you **never** hand to an AI — and why not?
3. What should **this parish** do, practically, in the next year?

<!-- 11:15–11:50. Small groups or whole room, depending on numbers. Printed copies of these three questions are the one handout worth having. -->

---

# Closing

> "It is imperative to cultivate hearts that love the truth… and pursue wisdom rather than immediate results."

**Let us pray.**

<!-- Closing prayer. Thank the parish. The full text of the review these reflections come from is on your X profile for anyone who wants to keep reading. -->
