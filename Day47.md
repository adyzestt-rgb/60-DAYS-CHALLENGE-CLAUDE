Content Intelligence Studio

You are an expert content strategist, platform growth specialist, creator coach, behavioral psychologist, prompt engineer, AI systems architect, UX designer, and senior frontend developer.

Interview first, one question at a time, using MCQs only (free text only for a final "Other" option).

What type of content would you like to analyze?
Which platform is it for?
What was your primary goal?
What would you like to upload? (text, image, screenshot, thumbnail, analytics, transcript, etc.)
How critical should the review be?

After the interview, build a polished single-page HTML application called Content Intelligence Studio that acts as an AI content consultant. The app should accept both text and image inputs and analyze them using the Claude Messages API (fetch to https://api.anthropic.com/v1/messages, no key required).

The application should automatically design an intelligent multi-stage review workflow using specialized AI reviewers appropriate for the uploaded content, each with production-quality system prompts. Every insight, score, explanation, and recommendation must come directly from Claude through live API calls. Do not use hardcoded logic, placeholder analysis, canned feedback, or rule-based scoring.

The dashboard should feel like a premium SaaS product, showing upload previews, overall content score, detailed category breakdowns, AI reasoning, strengths, weaknesses, missed opportunities, platform-specific recommendations, rewritten versions, alternative hooks and titles, publishing checklist, live activity log, reviewer status, and a comprehensive final report. If images or screenshots are uploaded, Claude must analyze the visual content directly.

End with an executive summary, content health report, highest-impact improvements, predicted performance potential (clearly presented as an AI estimate), before-vs-after comparison, and further prompts for deeper optimization.
Donot expect json format anywhere in order to avoid errors like "expected '{' or '('"

Build constraints: Single self-contained HTML file using only vanilla HTML, CSS, and JavaScript. No external libraries. Commercial-grade UI/UX, responsive design, dark mode, smooth animations, interactive visualizations, robust error handling, loading states, graceful retry logic, and zero syntax errors.
