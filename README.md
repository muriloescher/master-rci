# Master's Study Repository

## Repository structure

Each course folder follows the same local structure:

- `code/`
- `exercises/`
- `past-exams/`
- `slides/`
- `notes/`

The `code/`, `exercises/`, `past-exams/`, and `slides/` folders are kept locally and are not pushed to this repository.
Only content written by hand in each course's `notes/` subfolder is versioned here.

## Local study assistant setup

An MCP server is set up locally to use materials from the course folders and support my study workflow.
It is accessed locally through OpenCode together with a ChatGPT subscription.
This setup lets me use my course materials without uploading files directly to ChatGPT.

## Tools and workflow

The tools I currently use are:

- **Google Keep** as the central dashboard for courses, tasks, and goals (see structure below).
- **Google Calendar** as my central calendar, where I place time blocks for everything: study blocks, general routine, work, and social activities.
- **Handwritten note-taking** for everything, since I find that writing by hand improves learning.
- **Samsung Notes** to annotate course PDFs and keep handwritten notes.
- **Syncthing** to keep course folders synchronized between laptop and tablet.
- **Ubuntu + i3** on my laptop, with **Zathura** as the main PDF viewer.
- **Vim and VS Code** for coding.

## Google Keep dashboard structure

Google Keep is used as a central control dashboard.
There, pinned notes mark the current courses, as well as other personal todo and goals notes.
"Normal" notes (neither pinned nor archived) represent current-life-relevant information.
Past courses or unneeded info is consequently archived.

For every course, there is one note which serves as an overview of everything related to this course.
The template is as follows:

```text
🚀 CURRENT FOCUS
current exercise sheet OR project task
optional short clarification


📦 UPCOMING / LATER
next exercise sheet
future assignment
project milestone


⚠️ WEAK SPOTS
concepts that repeatedly cause difficulty
math gaps discovered during exercises
implementation confusions


💡 IDEAS / QUESTIONS
questions for tutorials
connections between topics
possible extensions


🗺 COURSE MAP (reference only)
list of lecture topics
conceptual structure of course


Course structure:
short description of evaluation format
(example: exercises + coding + project)
```

"Current Focus" is where the action happens.
Exercise sheets or programming tasks being worked on are here.
A small, optional status note may serve as a replacement for a complex Kanban board.
For ex. "Stuck on problem 2", or "Start problem 3".

The goal is to avoid having a huge, daunting to-do list which is slowly ignored into oblivion.
This should contain at most 2 items.
Splitting an exercise sheet into "Sheet 1 Problem 1", "Sheet 1 Problem 2", and so on, would lead into micromanaging, making organisation more of a problem than the actual learning.
Which, again, is not the goal.
So we keep it simple :).

"Upcoming / Later" is the backlog for coming sheets, assignments or project milestones.
This can be filled as each sheet appears, or at once in the beginning of the semester if the assignments are clear from the start (i.e. one sheet per week).
I usually put everything here.
Dragging the item into the current focus is the mental switch, which makes this big list not a problem for me, personally.

Weak spots should document clear understanding gaps, aiming at clearing them as soon as one appears.
Ideas/questions are kind of a dumping ground for things I want to ask in a tutorial when given the chance, or low-priority things to keep in mind.
The course map gives an overview of all weeks and their respective topics.
I find this nice to maintain an eye over the passing of time, which seems to be speeding up lately.
Course structure gives a quick reminder on what the course actually entails, if exercise sheets, extra exercises, projects, coding assignments and etc.

## Note workflow

1. All course material is downloaded into the corresponding course folder on my laptop.
2. Through Syncthing, the same folder structure is available on my tablet.
3. On the tablet, I import PDFs into Samsung Notes and work on them by hand.
4. When I want to keep a result, I export it back into the `notes/` subfolder of that course.
5. Syncthing brings the exported file back to my laptop automatically, and it is then available in this repository.

## Time management and study strategies

I use time-blocking to organize myself.
With the same goal of avoiding unnecessary organizational complexity (as in my Keep template), I avoid blocks like "1h - Study Machine Learning".
Instead, I use two study block types:

- **Deep Study**: usually 2h30 to 4h
- **Light Study**: usually 1h

Deep study happens early in the day and goes up to a maximum of 7 hours total (including breaks).
This is where I tackle exercise sheets, hard conceptual understanding, and self-testing.
Basically, this is where I try to use my head a lot.

The three days where most studying happens are the two non-working days during the week and Saturday.
On every weekday, there is one light study session in the evening.
That is where I watch lectures, do some light coding work, and do tasks that are useful but not as taxing as deep study tasks.

On Sunday, there is one 3-hour morning review session.
I start by going through all content from the previous week for every course (through my head), then writing down:

- the most important things I learned
- the biggest difficulties I had (or still have)

I then try to explain those points on my whiteboard.
This works as a spaced review session with a lot of free recall.

After this, I create 1-2 Anki cards per course with the most important concepts, connections, and ideas from the week.
Then I prime (skim) the next week's content, so my head is already prepared for the following study sessions and starts structuring things in advance.

In total (including breaks), the baseline weekly plan is:

- 19h30 of deep work
- 5h of light work
- 3h of review

The actual deep-work and review time is likely around 3 hours less if all breaks are discounted.
So the practical total is around `16h30 + 5h + 3h = 24h30` of focused work per week.

If needed, I use part of my free time on Saturday and Sunday to study more.
My goal is always to maximize the efficacy of my study hours.

I will describe the study strategies later.
