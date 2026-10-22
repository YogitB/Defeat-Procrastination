# Defeat-Procrastination

Motto: Find out why you're stuck, then take one tiny step.

Live app: https://yogitb.github.io/Defeat-Procrastination/


Category: Education and Access along with Health and Wellbeing

The conflicting problem:

Putting things off is not created by lazyiness and lack of motivation. Instead people put things off because starting feels bad. Reasons include mental problems, fear of failing, lack of understanding. Current apps and solutions  treat all procrastination the same (a to-do list, a timer), and this does not fix the problem.

My community is the students and classmates in my High School.

Observations from the survey: Personally, I tend to put off things right before the due date such as assignments, deadlines, and chores. I noticed this trend among many other of my classmates that I surveyed presenting an common problem. I noticed this and its because many are not brave to go on with the task.

Google form questions
How often do you start assignments the night before? , 6 of 9 said "Often" or "Almost always" (3 each). The other 3 said "Sometimes". Nobody said "Never".
What most often stops you from starting? . Too tired (3), it's boring (3), I don't know where to start (1), it feels too big (1), other (1). 
How much does putting things off stress you out? (1 to 5) . Average of 3.1.
Would a tool that helps you find your reason and take one tiny first step be useful? . Yes (5), Maybe (2), No (2) .

Limits and constrictions: This is a small group of people I know which I interviewed. Every person is different which makes their responses unique.

What people asked for:
One person asked for a way to  staying consistent.
One person wanted help for building practice questions. I didn't build that, and I addressed the problem by referring study website links on my website.





What it does:
It calls the task that you are procrastinationg on. Next it figures out where and why you are stuck. After it builds custom steps and creates a techinque. The AI crafts a 4-step plan for you to get on track. You can run a timer for specific strategies.



This is a study helper. **It is not therapy and not a diagnosis.** It points people to a trusted adult or school counselor if they feel overwhelmed or down.



How it works: It was built with HTML as the website. I use Cloudfare Worker for the API and AI integration. The CSS was coded for the AI and the UI was built with HTML and Javascript.



Built with:

HTML, CSS, JavaScript, Cloudflare Workers, Cloudflare Workers AI, GitHub Pages, Google Forms (for the survey), Google Fonts (Bricolage Grotesque, DM Sans, DM Mono).

Techniques used:

These are common, widely used study and habit techniques. I chose them and matched them to reasons myself, and I did not run a study to test how well they work.

Challenges I ran into throughout the journey:


CORS errors: My page was blocked from calling the Worker until I let it have access to the adresses, and I learned I had to test through a local server (Live Server) instead of opening the file directly. Through this I became familiar withe the Live Server extension.
Small AI models don't always follow instructions. I had to customize between the amount of maxTokens per each user allowing detail through the sentences.
I found the ai quite slow in the beginning because of it using an older outdated model. Small typo bugs that prevented elements from working.

 What I learned:
This was my first time experimenting with an API and inegrating it into an website. How to save data in storage. Asking real people and researching procrastination.


What I'd do next: 
As per the responses on the google form I would like everyone to reach a daily total of 5 logs a day on this such as a streak counter,
An bigger survey representing a bigger population.




How to run it yourself using the github repo

1. Download or clone this repo.
2. Open the folder in VS Code and run index.html with the **Live Server** extension.
3. If you do not have the live server extension you can click on it and it will lead you there.
3. The AI features need the Cloudflare Worker. Without it, the app still works using its built-in content.