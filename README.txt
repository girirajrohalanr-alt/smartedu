SMART EXAM MAKER — ZERO-BUDGET STARTER

Files:
- index.html: responsive website and first question-paper generator prototype
- manifest.json: installable PWA metadata
- sw.js: basic offline cache

Run locally:
1. Extract the ZIP.
2. Open index.html in a modern browser to test the generator.
3. For PWA install/offline features, deploy over HTTPS (for example, GitHub Pages or another free static host). Service workers do not work from file://.

First prototype limitations:
- It is a rule-based draft generator, not an AI model.
- It uses text pasted by the teacher/student; it does not contain official textbooks or syllabi.
- MCQ options are placeholders, not verified answer choices.
- Generated questions, answers, difficulty and marks must be reviewed by a teacher.
- All Indian boards are selectable as labels, but board-wise syllabus coverage has not yet been built.

Next development milestones:
1. Add proper question templates and answer-key generation.
2. Add board/class/subject/chapter syllabus mapping using permitted sources.
3. Add secure AI backend only after choosing a genuinely free/affordable API option.
4. Add user accounts and saved papers only after privacy/security design.
