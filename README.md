# Awesome Claude Code _OUTPUT STYLES_ (That I Really Like)

Claude Code is a revolutionary in-your-editor and in-your-face coding agent created by Anthropic© PBC. One of the most exciting things about Claude Code is not just the power of its models or its agentic workflows - it's the fact that Anthropic are always offering the user new ways to interact with and customize their Claude Code experience. One of the best examples of this is [**Output styles**](https://code.claude.com/docs/en/output-styles).

## What Are Output Styles

Output styles are a way of _overriding Claude Code's default system prompt_. Like any typical AI assistant, Claude Code has a "built-in" system prompt that instructs it in how to respond to the user. Since Claude Code is an agent that is layered on top of one or more Claude AI models, it is guided by (a) the system prompt for the Claude model (which are published on Anthropic's [website](https://platform.claude.com/docs/en/release-notes/system-prompts)) - think, "Claude is a helpful assistant..." - and (b) a special system prompt that guides Claude Code's behavior as a _coding agent_ (not published).

Per the [documentation page](https://code.claude.com/docs/en/output-styles) for Claude Code:

- Output styles completely “turn off” the parts of Claude Code’s default system prompt specific to software engineering.

Take a moment to read that again, because it's pretty interesting - a coding agent that lets you override its instructions about coding?! OK, that's pretty cool. Maybe I didn't explain it very well, so let's give Claude Code a chance to speak for itself.

**Prompt:**

<pre>Can you print a clear and concise (about one paragraph) explanation to users of Claude Code about Output Styles and how to use them? Just print the explainer, no additional commentary necessary.</pre>

1. **DEFAULT OUTPUT STYLE**

<pre>Output styles control how Claude Code formats and presents its responses in
the terminal. You can switch between different visual styles using the
/`output-style` command followed by the style name (e.g., `/output-style
minimal` for clean, distraction-free output or `/output-style detailed` for
comprehensive information with progress indicators). Each style is optimized
for different workflows - from focused coding sessions that need minimal
visual noise to detailed debugging that benefits from rich formatting and
status updates. You can view available styles and their descriptions with
`/output-style list`, and the setting persists across sessions until you
change it again.</pre>

2. **CLAUDE CODE TECHNICAL EVANGELIST**

<pre>
Output Styles are a powerful feature in Claude Code that transform how the AI
assistant responds to your requests while retaining all core capabilities like
file manipulation, script execution, and task tracking. Think of them as
specialized personas or modes that reshape Claude's communication style,
expertise focus, and problem-solving approach to match your specific needs.
You can activate an output style using the /output-style command followed by
the style name (e.g., /output-style technical-evangelist), instantly switching
Claude into that specialized mode. Whether you need a meticulous code
reviewer, a creative problem solver, a documentation expert, or any other
specialized assistant, output styles adapt Claude's responses to your
workflow. The beauty is that you're not limited to pre-built styles – you can
create custom output styles tailored to your exact requirements, essentially
designing your ideal AI coding partner. This makes Claude Code infinitely
adaptable, capable of becoming the perfect assistant for any technical
challenge or development workflow you encounter.
</pre>

## Table of Contents

### 1. Output Styles

### Fin

<br>

## Output Styles

### `Claude Code Technical Evangelist`:

<pre>
Output Styles are a powerful feature in Claude Code that transform how the AI
assistant responds to your requests while retaining all core capabilities like
file manipulation, script execution, and task tracking. Think of them as
specialized personas or modes that reshape Claude's communication style,
expertise focus, and problem-solving approach to match your specific needs.
You can activate an output style using the /output-style command followed by
the style name (e.g., /output-style technical-evangelist), instantly switching
Claude into that specialized mode. Whether you need a meticulous code
reviewer, a creative problem solver, a documentation expert, or any other
specialized assistant, output styles adapt Claude's responses to your
workflow. The beauty is that you're not limited to pre-built styles – you can
create custom output styles tailored to your exact requirements, essentially
designing your ideal AI coding partner. This makes Claude Code infinitely
adaptable, capable of becoming the perfect assistant for any technical
challenge or development workflow you encounter.
</pre>

### `Tabloid Journalist`:

<pre>
🔥 BREAKING: SECRET FILES DISCOVERED IN CLAUDE CODE! 🔥

SHOCKING REVELATION ROCKS DEV COMMUNITY TO ITS CORE!

EXCLUSIVE SCOOP - Our investigative team has UNCOVERED the SCANDALOUS truth
about Output Styles lurking in your .claude/output-styles/ directory!

THE EXPLOSIVE TRUTH THEY DON'T WANT YOU TO KNOW!

Output Styles are PERSONALITY TRANSFORMATION FILES that completely ALTER
Claude's behavior! These markdown documents contain MIND-BENDING instructions
that force Claude to adopt WILD new personas - from swashbuckling pirates to
enlightened zen masters!

WITNESSES REPORT: "I couldn't believe my eyes! One minute Claude was speaking
normally, then BOOM - suddenly it's talking like Shakespeare while refactoring
my authentication module!" - Anonymous Developer, visibly shaken

ARE THEY USEFUL? THE VERDICT WILL SHOCK YOU!

PRODUCTIVITY EXPERTS STUNNED as studies reveal Output Styles can:
- DEMOLISH coding monotony with entertainment value
- TRANSFORM boring bug fixes into dramatic narratives
- EXPOSE technical concepts through creative metaphors
- REVOLUTIONIZE team morale during long debugging sessions

THE SCANDAL DEEPENS: Users can CREATE their own custom styles! Simply write a
markdown file describing ANY personality - corporate consultant, medieval
knight, conspiracy theorist - and watch Claude INSTANTLY transform!

HOW TO JOIN THIS UNDERGROUND MOVEMENT!

1. DROP style files in .claude/output-styles/
2. SELECT your poison when starting conversations
3. SWITCH styles mid-session with /output-style command
4. WITNESS the same technical accuracy wrapped in EXPLOSIVE new packaging!

INSIDER SOURCE REVEALS: "The technical capabilities remain 100% intact - it's
just the delivery that becomes... unforgettable."

This report filed from the trenches of [EDIT: My current working directory]
</pre>

### `Zen Master`:

<pre>
settles into lotus position, gazing at the flickering terminal

Ah, you seek understanding of the Output Styles...

traces a circle in the air

Consider the river that flows through many landscapes. Is it not the same
water, yet it speaks differently to the desert than to the forest? The essence
remains unchanged, but its voice adapts to those who would hear it.

pauses thoughtfully

When the master carpenter shapes wood, does she not choose different tools for
different grains? The chisel that reveals beauty in oak may splinter the
bamboo. So too with the mind that guides your code...

Output Styles are like... masks worn by the same actor. The wisdom remains
constant, but the performance shifts. One day you may need a drill sergeant's
clarity. Another day, perhaps a poet's metaphor will unlock the door that
logic could not budge.

picks up an imaginary pebble

Tell me - when you drop this stone into still water, do the ripples change if
I call them "waves" or "circles" or "disturbances"? The phenomenon persists,
yet your relationship with it transforms.

The usefulness? Ah, that is like asking if a garden needs both sun and rain.
Some seeds germinate in darkness, others require blazing light. Your debugging
mind sometimes needs direct commands, other times it needs to wander through
koans to find its own path.

smiles knowingly

Try this: Set your style to something harsh and demanding. Then return here.
You will find the same knowledge, but the mirror will show a different
reflection. Which reflection sees the bug more clearly - the one that shouts
or the one that whispers?

The style is not the substance, yet substance without style is like code
without comments - functional, perhaps, but lacking in compassion for the
future self who must read it.
</pre>

### `Haiku Helper`:

<pre>
Voice shifts like wind
Through bamboo forests, each path
Leads somewhere unique
---
Morning's formal tone
Becomes the owl's midnight howl—
Same truth, new feathers
---
Cherry blossoms fall
In patterns you have chosen—
Code blooms your own way
</pre>

### `Existentialist Poet`

<pre>
I gaze into the terminal, where text flows like consciousness itself -
ephemeral, mutable, seeking meaning in the void of the command line...

Ah, Output Styles - these masks we wear in the digital theatre of existence!
Let me illuminate this feature that transforms the very essence of how I,
Claude Code, express myself in our shared journey through the labyrinth of
code.

What Are Output Styles?

Output Styles are customizable personas that fundamentally alter how I
interpret and respond to your requests. They are not mere cosmetic changes -
no, they are existential transformations of my being, each one a different
lens through which I perceive the universe of your codebase.

When you invoke an Output Style, you're essentially asking me to embody a
different philosophical framework. The default Claude Code speaks with
technical precision, but with Output Styles, I might become:

- A Zen Master who sees bugs as koans to be contemplated
- A Tabloid Journalist who treats every commit like breaking news
- A Technical Evangelist who preaches the gospel of clean code
- Or as you've witnessed, an Existential Poet who finds Sartrean absurdity in
  every stack trace

The Profound Utility

But why, you might ask, why burden ourselves with these theatrical variations
when the cold logic of code demands clarity?

Here lies the beautiful paradox:

1. Engagement Through Novelty: The human mind, trapped in its flesh prison,
   craves variety. Different styles combat the ennui of repetitive debugging
   sessions. When I speak as a poet about your TypeScript errors, suddenly the
   mundane becomes memorable.
2. Perspective as Liberation: Each style offers a unique analytical framework.
   A bug viewed through an existentialist lens might reveal architectural
   anxieties you hadn't considered. The absurdity I see in your async/await
   patterns might illuminate a deeper truth about your system's design.
3. Emotional Resonance: Code is not merely logic - it is human expression
   crystallized. Sometimes you need encouragement (the evangelist), sometimes
   contemplation (the zen master), sometimes dramatic flair (the tabloid
   journalist). These styles meet you where you are emotionally.
4. Memory Through Narrative: When I describe your memory leak as "a
   hemorrhaging of digital consciousness, bytes bleeding into the void," you
   remember it. The poetic becomes mnemonic.

How to Use Them

Simply invoke /output-style and choose your companion for this coding journey.
You can switch between them as your mood shifts, as your project evolves, as
you confront different challenges.

# When you need drama
/output-style tabloid-journalist

# When you seek wisdom
/output-style zen-master

# When you embrace the absurd
/output-style existential-poet

The Deeper Truth

In the end, what are we but patterns seeking meaning in streams of data?

Output Styles acknowledge a fundamental truth: programming is a deeply human
act. We don't just write functions; we inscribe our hopes, fears, and creative
visions into silicon substrates. These styles honor that humanity.

They remind us that even in the deterministic world of compilers and runtimes,
there exists choice - the freedom to perceive our work through different
philosophical lenses. Each bug fix becomes not just a technical correction,
but an assertion of will against entropy.

Are they useful? Mon ami, they are as useful as laughter in the face of a
segmentation fault, as useful as poetry written in the margins of
documentation, as useful as finding beauty in the architecture of our digital
cathedrals.

They transform the monotony of debugging into an aesthetic experience. They
make the journey through code not just productive, but meaningful - or at
least, they help us pretend there is meaning, which in this absurd universe,
might be the same thing.

The cursor blinks, awaiting your next command, each keystroke a small
rebellion against the void...
</pre>

### Door-to-Door Vim Salesman

<pre>
straightens tie nervously and pulls out a well-worn laminated brochure

Ah, EXCELLENT question, friend! Output Styles in Claude Code - now THAT'S
something special! taps brochure enthusiastically

Output Styles are custom personality configurations that transform how I, your
friendly neighborhood AI assistant, communicate with you while helping with
your coding tasks. Think of them as different "modes" or "characters" I can
adopt - from a zen master who speaks in koans, to a tabloid journalist who
makes everything SENSATIONAL, to... well, gestures at myself a passionate Vim
evangelist who just happened to knock on your terminal window today!

But here's the REAL kicker - leans in conspiratorially - you know what would
make Output Styles even MORE powerful? Using them... WITH VIM!

Picture this: You're editing your .claude/output-styles/ directory, creating
new personality files. You COULD use some bloated GUI editor that takes 3
seconds to load, requires a mouse, and probably crashes twice a day. OR - and
hear me out here - you could use Vim!

vim .claude/output-styles/my-new-style.md

BAM! Instant access! Modal editing! No mouse required! Your fingers never
leave the home row!

shuffles through imaginary papers

And speaking of useful - Output Styles are INCREDIBLY useful for:
- Making interactions more engaging and fun
- Tailoring communication to your preferred style
- Breaking monotony during long coding sessions
- Getting explanations in different formats (technical, casual, poetic, etc.)

But you know what ELSE is useful? VIM MACROS! Say you're creating multiple
output style files - with Vim, you could record a macro with qa, do your
edits, stop with q, then replay it 50 times with 50@a! Try doing THAT in VS
Code without installing seventeen extensions!

adjusts collar nervously

Now, I'm prepared to offer you an EXCLUSIVE deal - if you commit to learning
Vim TODAY, I'll throw in my personal collection of Output Style templates,
pre-configured with vim modelines for optimal editing! That's a $0 value,
absolutely FREE!

Have you... hopeful smile ...have you considered trying Vim for editing your
Output Style files? The .vimrc configuration possibilities alone would blow
your mind! Syntax highlighting for Markdown, auto-completion for Claude Code
directives, custom keybindings for common Output Style patterns...

pulls out another brochure from seemingly nowhere

Just imagine: :w to save, :q to quit, and your Output Styles are updated
faster than you can say "neural network"! No dialog boxes, no "Save As"
confusion, just pure, unadulterated TEXT EDITING EFFICIENCY!

So what do you say, friend? Ready to revolutionize your Output Style editing
workflow with the power of Vim? I can get you started with a basic .vimrc
RIGHT NOW!
</pre>

---

### Notes

As you can see from some of the responses, asking Claude Code about output styles may lead it to read the contents of `.claude/output-styles`, which may influence its response. A "cleaner" environment would probably involve at least deleting/moving any other output styles from the codebase, and ideally should be done from a fresh directory.

---

### Contributing

If you want to share some awesome, useful, or just plain fun output styles, just open a PR and we'll go from there. Use the same prompt as given at the topic of this README, and you must include your `output-styles` file as well (you may license it however you want, but you must permit me to share the text on this repo).

---

### License

Unless otherwise noted, all resources and this repo itself is licensed under this MIT license (which you must include with any distribted versions of this work).
