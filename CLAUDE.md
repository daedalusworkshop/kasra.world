# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is "Kasra.World" - an Obsidian vault used to build a personal portfolio. The repository contains markdown files exported from Notion, representing various AI, creative, design projects.

## Repository Architecture

### Three-Tier Portfolio System
1. **Archive/Portfolio/** - Original Notion exports with messy formatting and UUID filenames
2. **reved portfolio/** - Cleaned, organized versions with proper categorization and structure
3. **personal_portfolio/** - Interview-based authentic rewrites using genuine voice and stories

### Current Active Workflow
The main development focus is on the interview-based portfolio rewriting system in `personal_portfolio/`:

- **interview_tracker.md** - Master status file tracking all projects through the interview→draft→complete pipeline
- **question_asking_guide.md** - Methodology for extracting authentic stories (anti-LinkedIn approach)
- **questions/** - Prepared interview questions for specific projects
- **interviews/** - Raw interview transcripts capturing authentic voice
- **drafts/** - Final rewritten portfolio pieces using authentic language
- **assets/** - Image files copied from other portfolio versions

### Portfolio Content Structure
Projects are categorized into:
- **AI Tools** - Prompts, interfaces, and AI-human collaboration tools
- **Art + Tech** - Creative technology experiments and exhibitions  
- **Design Projects** - Physical design and fabrication work
- **Creative Writing** - AI-generated and human creative work

## Working with This Repository

### Interview-Based Portfolio Development

#### Core Process
- Use `question_asking_guide.md` for conducting authentic project interviews
- Track progress through `interview_tracker.md` status system (📋→🎤→💬→✍️→✅)
- Focus on "telling a friend over coffee" rather than professional presentation
- Capture exact words and preserve natural voice in interviews
- Hunt for specific moments, real reactions, and honest assessments

#### Two-Part Interview Approach
Every interview should cover:
1. **Project Story** - Get the authentic human experience of making the thing
2. **Presentation Strategy** - Figure out the most effective way to show THIS specific project

Don't default to essay format for everything. Different projects need different approaches:
- Technical walkthroughs, visual demonstrations, story-driven narratives, or interactive experiences
- Ask: "What's the best way to convey what makes this project special?"

#### Critical Question Types
**Scene-Setting:** "Walk me through the exact moment when..." "What was going through your head when..."
**Reality Check:** "But what ACTUALLY happened?" "Come on, what went wrong first?"
**Human Reaction:** "What did [specific person] say when they saw this?" "Who was the first person you showed this to?"
**Emotional Stakes:** "What were you trying to prove?" "When did you think 'oh shit, this might actually work'?"
**Money/Time Reality:** "How much did this actually cost you?" "Was it worth it?"

#### Voice Capture Techniques
- Record exact words and specific phrases - don't paraphrase in the moment
- Follow their energy - when they get excited, dig deeper
- Preserve contradictions and mixed feelings rather than resolving them
- Note natural speech patterns, hesitations, and "ums" that show real thinking

#### Style Evolution Discovery (From Mr President Case Study)
Through the Mr President project, we discovered a critical style evolution pattern:

**V1 (Too Casual):** Raw interview transcription feels unprofessional and scattered
- Direct quotes: "So much iterating, oh my god"
- Stream of consciousness flow
- Missing professional context

**V2 (Too Corporate):** Over-correction into sanitized professional language
- "Technical achievement," "workflow optimization," "professional relevance"
- Lost authentic voice and personality
- Sounds like every other portfolio

**V3 (Just Right):** Professional but preserves authentic voice
- "White toner printing is tricky" - keeps specific, honest details
- "I could go from an idea to a physical object in a few hours" - clear but not corporate
- Maintains conversational tone while providing professional context

#### Style Guide Principles
Based on V3 success:

1. **Preserve Authentic Details:** Keep specific technical struggles and honest reactions
2. **Professional Context:** Add enough background for portfolio viewers to understand significance
3. **Conversational Structure:** Use natural transitions and casual explanations
4. **Avoid Corporate Speak:** No "key learnings," "technical achievements," or abstract frameworks
5. **Show Real Process:** Include failures, iterations, and actual costs
6. **Concrete Specifics:** Replace generic insights with specific tools, techniques, and outcomes

#### Workflow Tools & Discoveries

**Interview Versioning System:**
- Multiple draft versions (v1, v2, v3) help refine style without losing progress
- Each version serves as a stepping stone toward the final voice
- Keep all versions for reference and learning

**Technical Documentation Approach:**
- Include specific tool names and versions (e.g., "Hunyuan 3D-2.1 via Krea.ai")
- Document actual costs and time investments
- Show failed attempts alongside successes
- Preserve exact technical processes for repeatability

**Voice Preservation Techniques:**
- Capture hesitations and natural speech patterns in interviews
- Note specific phrases that reveal personality ("So much iterating, oh my god")
- Preserve contradictions and mixed feelings rather than resolving them
- Follow energy and enthusiasm in responses - dig deeper where they get excited

**Client Collaboration Insights:**
- Working with friends as clients provides unique feedback opportunities
- Document the human dynamics, not just the project outcomes
- Include how relationships influenced the creative process

### File Organization
- Each project has corresponding files across all three portfolio tiers
- Assets are shared between `reved portfolio/assets/` and `personal_portfolio/assets/`
- Original files in Archive maintain UUID naming from Notion export
- Use consistent naming when creating new versions in personal_portfolio

### Content Philosophy

#### Core Values
- Authentic human stories over polished professional narratives
- Real failures, costs, and learning moments over sanitized success stories
- Specific details and genuine reactions over abstract insights
- Voice preservation and conversational tone over formal documentation

#### Learned Refinements (From Mr President Experience)
- **Balance authenticity with professionalism:** Raw transcripts need structure but shouldn't lose personality
- **Specific technical details matter:** Include exact tools, costs, timeframes, and failure points
- **Process over outcome:** Show the messy journey, not just the polished result
- **Human dynamics are content:** How people reacted, what they said, relationship dynamics
- **Preserve natural language:** "White toner printing is tricky" > "Implemented advanced printing methodologies"
- **Multiple perspectives:** Show both personal satisfaction and practical learning outcomes

## Reference Examples

### Mr President Case Study - Template Success
The Mr President project serves as the reference template for successful interview-based portfolio development:

**What Worked:**
- Interview captured authentic moments: "So much iterating, oh my god"
- Technical specificity: "Hunyuan 3D-2.1 via Krea.ai" and "white toner printing"
- Honest cost assessment: "$200 because I had to buy filament, shirt printing, materials"
- Process documentation: Showed failed attempts alongside successes
- Human relationships: Working with Grant as friend-client, group dynamics
- Style evolution: V1→V2→V3 refinement process yielded professional but authentic final piece

**Key Quote Examples from Final Draft:**
- "White toner printing is tricky—you need the right heat and pressure settings"
- "I could go from an idea to a physical object in a few hours"
- "Grant was a great client to work with since I could be completely honest with him"

**Structure Elements:**
- Conversational section headers ("Figuring It Out Through Trial and Error")
- Specific tool workflows with visual documentation
- Honest investment/outcome assessment
- Forward-looking applications without abstract frameworks

## Development Context

This is a documentation/portfolio repository rather than a traditional codebase. There are no build tools, package managers, or testing frameworks configured. The content is entirely markdown-based for use with Obsidian.

## Interaction Guidelines

- You don't have to ask permission for anything that isn't destructive. Just go ahead and do it then let me know after the fact. If you're uncertain if the act is destructive, err on the side of caution.

## Key Workflow Commands

Since this is a documentation repository with no build tools, the main workflow involves:
- **Status tracking**: Update `personal_portfolio/interview_tracker.md` when progressing projects through pipeline stages
- **Asset management**: Copy images between `reved portfolio/assets/` and `personal_portfolio/assets/` as needed
- **File organization**: Maintain consistent naming when creating new versions in personal_portfolio (use underscores, match existing patterns)

## Critical Files for Portfolio Development

- **interview_tracker.md** - Master status file tracking all projects (📋→🎤→💬→✍️→✅)
- **question_asking_guide.md** - Methodology for conducting authentic interviews
- **portfolio_style_guide.md** - Style patterns learned from Mr President evolution (v1→v3)
- **questions/** folder - Project-specific interview templates
- **interviews/** folder - Raw transcripts preserving authentic voice
- **drafts/** folder - Final rewritten pieces using natural language

## Current Project Status (Check interview_tracker.md for updates)

**Completed:** Mr President Case Study, What the Hell Is Water?, Every Intelligence
**Ready for Interview:** Half Human (questions prepared)
**Pending Questions:** Personality Documentation, Poetry Matchmaker, Sparring Partner, On Your Final Injury, The Aviator, Resonance Device

## Red Flag Questions to Avoid

**Professional/Generic (Bad):**
- "What was your design process?"
- "How did you approach this challenge?" 
- "What were the key learnings?"

**Human/Specific (Good):**
- "What was the first version of this that completely sucked?"
- "When did you realize you had no idea what you were doing?"
- "What did your mom say when you tried to explain this to her?"

**Test:** Would this question get an answer that could come from anyone, or only from this specific person about this specific experience?

## Status System Workflow

Projects follow this pipeline:
1. **📋 Pending** - Questions not yet prepared
2. **🎤 Ready** - Questions prepared, awaiting interview  
3. **💬 Interviewing** - Currently in interview process
4. **✍️ Drafting** - Interview complete, writing in progress
5. **✅ Complete** - Final draft ready