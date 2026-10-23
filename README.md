# Defeat-Procrastination

Motto: Find out why you're stuck, then take one tiny step.

Live app: https://yogitb.github.io/Defeat-Procrastination/


Category: Education and Access along with Health and Wellbeing

What is the specific problem, and how do you know it's real?:

Putting things off is not created by lazyiness and lack of motivation. Instead people put things off because starting feels bad. Reasons include mental problems, fear of failing, lack of understanding. Current apps and solutions  treat all procrastination the same (a to-do list, a timer), and this does not fix the problem. Many of the tools that we have today organize tasks while shifting away from addressing the reason that the student is struggling.
My community is the students and classmates in my High School. They are all my target community as I wish to connect this project and expand it as students can benefit from operating deadlines.

Observations from the survey: Personally, I tend to put off things right before the due date such as assignments, deadlines, and chores. I noticed this trend among many other of my classmates that I surveyed presenting an common problem. I noticed this and its because many are not brave to go on with the task. This helped me shape the finding from the app to focusing on the barriers that prevent classmates from working productively.

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
1. Identify the task by recording what the student enters
2. It discovers what the main obstacle is from asking the user questions
3. The AI generates a 4 step plan customized for the user to maintain focus
4. An timer is included to set small study goals along with streaks and an analysis of study strategies




This is a study helper. **It is not therapy and not a diagnosis.** It points people to a trusted adult or school counselor if they feel overwhelmed or down.



How it works: 
1. I used the HTML to create elements to create a trendy vide for the students such as large buttons and specific fonts.
2. The CSS designed the appearance of the website such as the layout and the spacing in inputs.
3. Javascript helped the website become interactive by responding to users actions and reading inputs.
4. Cloud flare workers acted as the backbone by supporting the backend code for the AI services.
5. The AI from CLOUDFLARE WORKERS generated responses and built a plan based for the applicants.



Built with:
1. HTML is used for the strucutre of the page and the buttons
2. CSS is used for the interface and styling of the webpage. 
3. Javascript is used for the app logic and for the interactions of elements
4. Cloudflare Workers was integrated for the AI requests through the backend API endpoint
5. Cloudflare Workers AI is used for all AI responsibilities in the page
6. Github pages for the website hosting.


Techniques used:

These are common, widely used study and habit techniques. I chose them and matched them to reasons myself, and I did not run a study to test how well they work. The matches based on the obstacles reflect my own capability to make decisions.

Challenges I ran into throughout the journey:


CORS errors/API integration: My page was blocked from calling the Worker until I let it have access to the adresses. I primarily reversed engineered through how browser requests work and how to configure the backend. Through this I learned I had to test through a local server (Live Server) instead of opening the file directly. Through this I became familiar withe the Live Server extension.
Small AI models don't always follow instructions. I had to customize between the amount of maxTokens per each user allowing detail through the sentences.
I found the ai quite slow in the beginning because of it using an older outdated model. Small typo bugs that prevented elements from working.

What I learned:
This was my first time experimenting with an API and inegrating it into an website. Through this hackathon I gained experience with frontend developement, exposure to backend requests, AI integration, how to save data in storage while asking real people and researching procrastination.


What I'd do next: 
As per the responses on the google form I would like everyone to reach a daily total of 5 logs a day on this such as a streak counter,
An bigger survey representing a bigger population.




How to run it yourself using the github repo

1. Download or clone this repo.
2. Open the folder in VS Code and run index.html with the **Live Server** extension.
3. If you do not have the live server extension you can click on it and it will lead you there.
3. The AI features need the Cloudflare Worker. Without it, the app still works using its built-in content.