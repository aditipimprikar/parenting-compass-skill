# Parenting Compass Generator

A Claude Code skill that helps you create a personalized parenting framework grounded in your values, practices, and goals.

## What This Does

This is a **generator skill** that guides you through creating your own custom "Parenting Compass" - a values-based decision-making framework you can use during emotionally charged parenting moments.

Instead of reacting from stress, exhaustion, or overwhelm, you'll have a clear framework grounded in YOUR specific values and goals to help you respond intentionally.

## What You Get

After a 10-15 minute guided conversation, you'll have:

- ✅ A custom skill file with your core parenting values
- ✅ A decision-making framework for hard moments
- ✅ Situation playbooks tailored to your child's age and your biggest challenges
- ✅ Reflection prompts that reconnect you to your values
- ✅ A tool you can invoke anytime: `/parenting-compass`

## Example Use Cases

The generator adapts to different parenting approaches:

- **Whole-Brain parenting** (connection-first, brain science-based)
- **Love and Logic** (natural consequences, teaching through experience)
- **Positive Discipline** (respectful, collaborative problem-solving)
- **Traditional + modern blend** (structure + empathy)
- **Your own unique approach** (whatever matters to you!)

## How It Works

1. **Invoke the skill:** `/create-parenting-skill`
2. **Answer guided questions** about:
   - Your child's age and your biggest challenges
   - Your parenting values and beliefs
   - Your current practices
   - Your long-term developmental goals
   - Your hardest parenting moment
3. **Review the synthesis** - I reflect back what I heard
4. **Get your custom skill** - Generated specifically for you
5. **Refine if needed** - Iterate until it feels right
6. **Use it anytime** - Type `/parenting-compass` when you need support

## Installation

### Prerequisites

- [Claude Code](https://claude.ai/code) installed (CLI, desktop app, or IDE extension)

### Install the Generator Skill

1. **Clone this repository:**
   ```bash
   git clone https://github.com/aditipimprikar/parenting-compass-skill.git
   ```

2. **Copy to your Claude skills directory:**
   ```bash
   cp -r parenting-compass-skill/create-parenting-skill ~/.claude/skills/
   ```

3. **Verify installation:**
   ```bash
   ls ~/.claude/skills/create-parenting-skill
   ```
   You should see `SKILL.md`

### Generate Your Personal Skill

1. **Open Claude Code** (CLI, desktop app, or IDE)

2. **Invoke the generator:**
   ```
   /create-parenting-skill
   ```

3. **Follow the guided conversation** (10-15 minutes)

4. **Your personalized skill will be created at:**
   ```
   ~/.claude/skills/parenting-compass/SKILL.md
   ```

5. **Use it anytime:**
   ```
   /parenting-compass
   ```
   Or just describe a parenting situation and it will load automatically.

## Example Generated Skills

The generator creates highly personalized skills. Here are two examples showing different approaches:

### Example 1: Whole-Brain Approach (Toddler, 19 months)

**Values:**
- Connection before correction
- Independence builds the brain
- All feelings welcome, some behaviors need limits

**Framework:** PAUSE (Pause, Attune, Understand, Soothe, Engage)

**Playbooks:** Meltdowns, when triggered, building independence, reflective listening

**Tone:** Brain science-grounded, empathetic, developmental

---

### Example 2: Love and Logic Approach (Toddler, 18-36 months)

**Values:**
- Teaching through consequences
- Actions have consequences
- Emotions expressed, not spiraling

**Framework:** TEACH (Take control, Evaluate, Allow consequences, Communicate, Hold boundary)

**Playbooks:** Transitions, discipline & boundaries, building work ethic

**Tone:** Practical, directive, consequence-focused

---

**Both are valid!** The generator creates what fits YOUR values and situation.

## Features

### Adaptive Questioning
- Age-appropriate questions based on child's developmental stage
- Follows up when answers are vague
- Notices contradictions and helps you clarify
- Stops when it has enough (doesn't over-question)

### Personalized Output
- Not a template with blanks filled in
- Uses your language and examples
- Includes only relevant playbooks for YOUR challenges
- Customized decision-making framework
- Tone matches your approach (brain-science vs. practical vs. spiritual, etc.)

### Iterative Refinement
- Shows you the generated skill
- Asks for feedback
- Refines based on your input
- You approve before it's saved

## What Makes This Different

Most parenting advice is one-size-fits-all. This tool:

- ✅ **Starts with YOUR values** (not someone else's philosophy)
- ✅ **Adapts to YOUR child's age** (toddler needs differ from school-age)
- ✅ **Focuses on YOUR hardest moments** (transitions, bedtime, whatever YOU struggle with)
- ✅ **Speaks in YOUR language** (brain science, consequences, connection - whatever resonates)
- ✅ **Lives where you work** (integrated into Claude Code, available anytime)

## Philosophy

This tool is based on research from:

- *The Whole-Brain Child* by Siegel & Bryson (brain science, integration)
- *Raising Good Humans* by Hunter Clarke-Fields (parent self-regulation, mindfulness)
- *Free-Range Kids* by Lenore Skenazy / Let Grow Foundation (autonomy, independence)

But it's **framework-agnostic** - it helps you clarify and operationalize YOUR values, whatever they are.

## FAQ

**Q: Do I need to know about parenting philosophies to use this?**  
A: Nope! The generator helps you discover what matters to YOU through questions. You don't need to have read any books.

**Q: What if I don't know my values yet?**  
A: That's exactly what the guided questions help you figure out. Start with what you want for your adult child, and work backwards.

**Q: Can I update my skill as my child grows?**  
A: Absolutely! Re-run `/create-parenting-skill` anytime your situation changes. Or just edit the `SKILL.md` file directly.

**Q: Will this work for multiple children?**  
A: The generator currently focuses on one child's age. If you have multiple ages, you might create separate skills or generalize to cover the range.

**Q: What if my partner has different values?**  
A: You could each create your own skill, then create a shared one that bridges your approaches. Or use it to clarify where you agree/disagree.

**Q: Is this only for "gentle parenting"?**  
A: No! It adapts to YOUR approach. Love and Logic, Traditional, Positive Discipline, RIE, Montessori, or your own blend - it works for any values-based framework.

## Technical Details

- **Skill format:** Markdown file with YAML frontmatter
- **Location:** `~/.claude/skills/parenting-compass/SKILL.md`
- **Invocation:** `/parenting-compass` or automatic when discussing parenting situations
- **Version control:** Includes git initialization for tracking changes
- **Size:** Generated skills are typically 250-400 lines (condensed) or 700+ lines (full version)

## Contributing

This is a personal tool, but if you'd like to suggest improvements:

1. Fork the repository
2. Make your changes
3. Submit a pull request with description of what you improved

Particularly interested in:
- Better question phrasing
- Additional parenting frameworks to support
- Edge cases the generator doesn't handle well

## License

[MIT](https://github.com/aditipimprikar/parenting-compass-generator/blob/main/LICENSE)

## Acknowledgments

Created by [Aditi Pimprikar](https://github.com/aditipimprikar)

Inspired by the need for parenting guidance that's grounded in individual values rather than one-size-fits-all advice.

Built for the [Claude Code](https://claude.ai/code) skills system.

## Support

Questions or issues? Open an issue in this repository or email me at pimprikar.aditi@gmail.com

---

**Remember:** Parenting is a practice, not perfection. This tool helps you reconnect with your values when emotions are high - which is exactly when you need it most. 💙
