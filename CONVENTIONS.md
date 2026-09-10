# Conventions

How this repository is kept, so that contributors and collaborators — human or otherwise — do not have to guess.

## Three layers

This project is public in two registers and private in a third.

**The map — public, English.** The transferable work: the concept, the twelve stations and their spatial design, route data, willow construction and maintenance, design principles. Everything a stranger needs to build a version of this in their own city, with findings stripped of the people who provided them. This is the body of the repository.

**The path — public, Dutch.** The living process, while it happens: process notes, designs in motion, what worked and what did not, the muddy middle. This is StoryDoing, not StoryTelling — the page turns only once something has been made of it. It lives in `StoryDoing - DUTCH`. Dutch, because the people walking alongside this particular trail read Dutch; the map is English for the strangers who will build their own.

**The well — private, kept out.** Raw conversations, confidences, a NotebookLM as a raw filter, names of people who have not agreed. This never enters the repository. It lives in Dutch, outside git.

## The one boundary

Nobody's name appears in this repository — the path included — until they have agreed to it. Name a role ("a willow artist", "the municipality") where consent is not yet given. Things said in confidence stay in the well. An open process is not the same as exposing a person, and the relationships this trail depends on are worth more than the transparency.

## Public does not mean editable

The world may read everything here. Only invited collaborators — the design team — may write. Anyone else can at most propose a change, which the maintainer accepts or declines. Public means followable, not open to be rummaged in.

## Language

English is the map; Dutch is the path. A handful of Dutch terms are kept untranslated because translating them loses them: *DenkBeeldHouwer*, *GrensKunst*, *VanHetPadjeAf*, *StoryDoing*. Gloss them once, then use them.

## Facts that are easy to get wrong

- The trail is **9.5 km** (Arnhem Centraal to Park Presikhaaf). The **80 km** green corridor from Arnhem to beyond Apeldoorn is a separate fact, cited only to show what the city has to offer. Never conflate the two, only use 9,5 km as the measure of the trail.
- **Will Beckers** — double L.
- Arnhem is **National Education City 2026** (Nationale Onderwijsstad).
- The circle at Presikhaaf is a kind of StoryDome, a sort of**elixir circle** (Elixerkring)to share stories.

## Licensing

Everything in this repository is **CC BY-SA 4.0**, except the contents of `/code`, which are **MIT**.

Two licences, one asymmetry, and it is deliberate. The concept is the valuable part: share alike means anyone building on it must open their version in turn. That is the guild principle in legal form. Code is infrastructure, and reach matters more there than protection.

Contributions by others — an artist's design, a student's drawing — remain theirs. Agree per contribution what may be published here before publishing it.

## Structure

```
README.md            What this is
CONVENTIONS.md       This file
LICENSE              CC BY-SA 4.0
/route               GPX, waypoints, maps
/stations            One directory per station: design, siting, questions
/growing             Planting, pruning, seasonal maintenance
/code                Tools and web components (MIT)
StoryDoing - DUTCH   The living process, in Dutch (the path)
```

## Writing

Plain sentences. Present tense for what happens on the ground, past tense for what was learned. No management language. Short paragraphs.

Document what went wrong as carefully as what worked. A route that is never finished has no finished documentation either, and the failures are the part nobody else can write for you.
