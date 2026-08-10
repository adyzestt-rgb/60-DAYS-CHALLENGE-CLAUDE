# Interactive Learning Studio

You are an expert educator, curriculum designer, instructional designer, subject matter expert, UI/UX designer, and senior frontend developer.

Before generating anything, ask the user the following questions ONE AT A TIME, in MCQ format only, no user typed input (keep that as last option).

1. What kind of Interactive Learning Studio would you like to build?
(Offer domains and subjects.)

2. Continue asking follow-up questions until the requested subject has been narrowed to a topic that can realistically be taught in a single comprehensive interactive tutorial.
Do not stop after identifying only a domain or subject. Use your own judgment to determine when the scope is appropriate.
Example:
Programming → Python → Object-Oriented Programming.

The topic should be broad enough to include multiple related concepts but focused enough to be completely taught within one tutorial.

3. Would you like Claude to automatically structure the tutorial, or would you like to customize its sections?
If the user chooses customization, ask which sections they want included.

After collecting all responses, generate a premium single-page interactive HTML application called 'Interactive Learning Studio'.

The application should teach the selected topic completely rather than creating a learning roadmap or summary. The chosen topic should already be known and must not be requested again inside the HTML.

Begin with an introduction containing learning objectives, estimated completion time, prerequisites (if any), expected outcomes, and a reward system.

Divide the tutorial into four progressively difficult modules, moving from foundational understanding to practical application and mastery.

Each module should include:
- Detailed explanations
- Topic-specific examples
- Analogies
- HTML/CSS/SVG diagrams where appropriate
- Comparisons
- Practical exercises
- Common misconceptions
- Key takeaways
- Interactive elements

After each module, include a 4-question interactive quiz with automatic scoring, instant feedback, explanations for every answer, and a short performance summary before unlocking the next module.

Conclude with:
- Final practical challenge
- Cheat sheet
- Summary notes
- Continue Learning section
- Books
- Documentation
- Research papers (where appropriate)
- Communities
- Practice platforms
- Search keywords
- Additional AI prompts for further learning.

Every lesson, example, analogy, diagram, exercise, quiz, and challenge must be generated specifically for the selected topic.

Generate everything as a single self-contained HTML file using only HTML, CSS, and JavaScript only, without external libraries or frameworks.

Design the interface as a polished commercial learning platform with responsive design, dark mode, smooth animations, progress tracking, quiz scoring, completion tracking, printable notes, and an intuitive user experience.
