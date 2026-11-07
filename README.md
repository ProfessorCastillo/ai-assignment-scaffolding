# AI Assignment Scaffolding

A Claude skill that helps faculty design how students use AI on a specific assignment, so the thinking and voice in the final work stay the students' own.

## What it does

You tell Claude about an assignment. Claude interviews you about the course, the stakes, and which parts of the work have to stay the student's. Then it builds three documents tailored to that assignment:

1. **Student handout.** The steps students follow, with what to turn in at each one.
2. **Rollout timeline.** A dated schedule of steps, due dates, and class touchpoints.
3. **Instructor guide.** How to introduce the scaffold, grade the process, check authenticity, and handle common problems.

The scaffold has nine optional steps in three phases: before students open the AI tool, while they work with it, and before they submit. Students form their own view first, use AI to challenge and widen it, and finish by checking that they can defend every sentence. A low-stakes assignment might use two steps; a capstone might use all nine. You choose which ones.

The framework is adapted from Nufar Gaspar's "deslopify" playbook on *The AI Daily Brief* ("How to Deslopify Your AI," Nov 2, 2026): https://aidailybrief.ai/e/2026-11-02

> **This is an experimental skill.** Treat its recommendations as a starting point, not a standard. Weigh each one against your course's AI learning objectives and your students' experience with AI.

---

## Install it (no GitHub experience needed)

### Option A: Claude website or desktop app (most people)

1. **[Download the skill (ZIP file)](https://github.com/ProfessorCastillo/ai-assignment-scaffolding/raw/main/download/ai-assignment-scaffolding.zip)**. Don't unzip it.
2. In Claude, go to **Settings → Capabilities** and make sure **Skills** is turned on.
3. In the Skills section, click **Upload skill** and choose the ZIP file you downloaded.
4. Start a new chat and type something like: *"Help me design an AI scaffold for my final paper assignment."*

If you don't see a Skills option, your account or institution may not have skills enabled yet. Ask your IT or Claude administrator.

### Option B: Just the instructions file

If you only want the instructions (to read them, or to paste them into a Claude Project's instructions):

**[Download SKILL.md](https://github.com/ProfessorCastillo/ai-assignment-scaffolding/raw/main/skills/ai-assignment-scaffolding/SKILL.md)**

If the file opens in your browser instead of downloading, right-click the link and choose **Save Link As…**

### Option C: Claude Code (for people who use the terminal)

```
/plugin marketplace add ProfessorCastillo/ai-assignment-scaffolding
/plugin install ai-assignment-scaffolding@ai-assignment-scaffolding
```

---

## Using it

Once installed, start a chat and describe your assignment. Pasting your assignment prompt or syllabus saves time, since Claude will pull the details from it instead of asking. Have your actual dates handy (term dates and the assignment's release and due dates) so the timeline comes out right.

The skill does not need student names or records. Don't share them.

## Feedback

Questions, suggestions, or stories from your classroom are welcome. Open an issue on this page, or email Vince Castillo at castillo.230@osu.edu.
