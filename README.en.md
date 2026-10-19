# Learning Program Designer

**A Claude skill that turns a training request into a program that changes what people do at work.**

🇧🇪 [Nederlandstalige versie](README.md) · 📄 [Examples](examples/)

Describe the request ("our team leads hardly give feedback, design a training of max. 1 day") and get a complete design: from need and objectives to session plans, transfer to the workplace and evaluation.

It works in English, Dutch and French: it replies in the language you write in.

## What the skill does

- **Starts from the performance problem**, not the content.
- **Says when training alone isn't the answer**, and what else is needed.
- **3–6 measurable performance objectives**; every activity serves one.
- **Before / during / after** journey with most time on practice, and transfer support afterwards.
- **Proportionate evaluation** using the Kirkpatrick levels.

## What you get

1. **Need and assumptions**
2. **Objectives**
3. **Program overview**
4. **Session plans** with timings that add up
5. **Transfer plan**
6. **Evaluation plan**
7. **Next steps**

See [examples/](examples/) for a full input and output.

## Who it's for

L&D and HR professionals, training managers, lecturers and consultants who design training, workshops, onboarding or learning journeys.

This skill is part of **[Claude Skills for Education](https://github.com/ThomasAiluminated/claude-skills-for-education)**, an open collection for education and L&D:
- [Edu Prompt Coach](https://github.com/ThomasAiluminated/edu-prompt-coach): ready-to-paste prompts for teachers, with the pedagogy behind them
- [Lesson Designer](https://github.com/ThomasAiluminated/lesson-designer): lessons designed from objective to exit check
- [Rubric Builder](https://github.com/ThomasAiluminated/rubric-builder): assessment rubrics with observable levels
- [Assessment Item Writer](https://github.com/ThomasAiluminated/assessment-item-writer): test and exam questions with answer key and feedback
- [Feedback Writer](https://github.com/ThomasAiluminated/feedback-writer): specific, actionable feedback on student work
- [Inclusive Lesson Adapter](https://github.com/ThomasAiluminated/inclusive-lesson-adapter): accessible lesson materials using UDL
- [Prompt Architect](https://github.com/ThomasAiluminated/prompt-architect): rough requests turned into strong prompts for Claude

## Install

**In Claude (web, desktop or mobile):**
1. Download [`learning-program-designer.skill`](learning-program-designer.skill)
2. Upload it under Skills in your Claude settings
   (or open the file in a Claude conversation and click *Save skill*)

**In Claude Code:** copy the `learning-program-designer/` folder to `~/.claude/skills/`.

Then just ask, for example *"design a three-week onboarding program for new lecturers"*. The skill starts automatically.

## Contributing

Ideas and improvements are welcome via an issue or pull request.

## License

[CC BY 4.0](LICENSE): free to use, adapt and share, with attribution.

---

Made by **Thomas Donvil**, [Ailuminated](https://ailuminated.org), AI literacy for education.
