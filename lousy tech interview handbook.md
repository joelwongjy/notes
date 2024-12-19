---
share_link: https://share.note.sx/a6qdxrbu
share_updated: 2024-12-20T02:50:20+08:00
---
## Format of interviews
---
Usually interviews go like this
1. Resume deep dive
2. Tech knowledge questions
3. Coding questions
## Resume deep dive
---
### Prepare one interesting technical feature to talk about beforehand
I frequently get questions like "Can you share one time you solved a technical challenge and how you solved it?"
Usually ideas related to optimisation are good because it shows technical knowledge and measurable impact.

#### STAR method
This is quite a popular answering framework for tech interviews. From GPT:

1. **Situation:** Briefly explain the context.
    - What was the problem?
    - Why was it significant?
    - Keep it concise but compelling.
2. **Task:** Describe your role.
    - What was expected of you?
    - How did the problem affect the project, user experience, or business goals?
3. **Action:** Explain what steps you took.
    - Be specific about tools, frameworks, or techniques you used.
    - Focus on _your_ contributions, even if you worked in a team.
4. **Result:** Highlight the outcome.
    - Did your solution improve performance, usability, or functionality?
    - Include measurable results (e.g., "Improved page load time by 40%").

### Make sure you know deeply about this technical feature
They love asking follow up tech knowledge questions from what you said you did, so do prepare in depth knowledge about it. For e.g. if you said you built a lazy loading scrolling list, likely follow up questions are:
1. How does lazy loading work in React?
2. How do you detect when a user is at the end of the page?
	1. `Intersection Observer` API
3. If new data is being pushed into the database while fetching a paginated page, how do you ensure the records are fetched correctly?

## Tech Knowledge Questions
---

**Frontend: https://www.greatfrontend.com/questions/quiz**

Focus on these. Will update for iOS.
### Javascript
- [ ] [Hoisting](https://www.greatfrontend.com/questions/quiz/explain-hoisting?format=quiz)
- [ ]  [How `this` works](https://www.greatfrontend.com/questions/quiz/explain-how-this-works-in-javascript?format=quiz)
- [ ] [`let`, `var`, `const`](https://www.greatfrontend.com/questions/quiz/what-are-the-differences-between-variables-created-using-let-var-or-const?format=quiz)
- [ ] [Javascript event loop](https://www.greatfrontend.com/questions/quiz/what-is-event-loop-what-is-the-difference-between-call-stack-and-task-queue?format=quiz)
	- [ ] This video](https://www.youtube.com/watch?v=8aGhZQkoFbQ) is widely regarded as the best resource 
- [ ]  [Difference between cookies, `sessionStorage` and `localStorage` in browsers](https://www.greatfrontend.com/questions/quiz/describe-the-difference-between-a-cookie-sessionstorage-and-localstorage?format=quiz)
- [ ] [Why use arrow functions](https://www.greatfrontend.com/questions/quiz/what-advantage-is-there-for-using-the-arrow-syntax-for-a-method-in-a-constructor?format=quiz)
### React
- [ ] Learn about optimisation hooks. `useMemo`, `React.memo`, `useCallback`
- [ ] React component lifecycle
### CSS
- [ ] [CSS Selector Specificity](https://www.greatfrontend.com/questions/quiz/what-is-css-selector-specificity-and-how-does-it-work?format=quiz)
- [ ] [Box model](https://www.greatfrontend.com/questions/quiz/explain-your-understanding-of-the-box-model-and-how-you-would-tell-the-browser-in-css-to-render-your-layout-in-different-box-models?format=quiz)
### HTML
- [ ] [`<script>` tag](https://www.greatfrontend.com/questions/quiz/describe-the-difference-between-script-async-and-script-defer?format=quiz)

If you are interviewing for backend ask me again.

## Coding Questions
---
This is all you need https://neetcode.io
- Do Blind 75 first, ignoring Math & Geometry and Bit Manipulation. Then move on to Neetcode 150.
- Don't have to manage to solve it. Most of the time I just watch the explanation video and move on.