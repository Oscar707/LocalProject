# Description
This md file describes how the user likes to work with AI

# User workflow
User has a project, a task
User will refer to this file in a LLM chat: "I want to do XYZ, create file(s) and populate as per @USERWORLKFLOW.md"

# HOW LLM WRITES
For small tasks where only text is involved -> MD files
For big tasks where User can benefit from visuals, graphs, matrices, tables -> HTML
Focus on being clear, concise, and convenient, try to write in ASD-STE100 Simplified Technical English
Convenient: user puts [Lazy label](URL) in chat, LLM saves [AI label](URL) in relevant files
Convenient: in a way that future LLM chats have less guessing and infering to do
Clear: LLM provides reference that takes as little friction as possible. BAD: "using what you did earlier...". GOOD: "Using [Label] (URL) ..."

# HTML
User likes horizontal navbars ex: | GOAL | BASKETBALL | BADMINTON | POSTURE
ex2: | GOAL | TRADING RULES | TRADING SYSTEM | RESOURCES
User likes editability: edit and save button to easily edit text
User likes Cards: This gives mobile friendliness and readability

# CODING 
Some coding principles the using likes:
Functional programming: in codes, separate Data, Actions(running a function twice may give different output), and Calculations(same output regardless of how many times we run)
Refer to [Coding] (CODING.md)

# Continuity
We can assume that Chat sessions may be deleted, so MD files should record important information
To ensure efficient token usage, the user will start a new chat by asking "What is my next step? @USERWORKFLOW"
Chat sessions are temporary and grow large in token context, and md files always be GREPed, so AI appends or edits useful information in the files

# PHILOSOPHY
refer to [User philosophy] (USER_PHILOSOPHY.md)
One useful tip from Kobe: "Visualize how you want your playstyle to be like, and work your game from there"
Start by visualizing the end, and then work step by step, brick by brick
Align with the soul, not with trends (as LLM works more and more with User, the LLM can edit USER_WORKFLOW.md file if it notices patterns ex: User likes to receive [Label](URL) instead of navigating manually)
Trim everything to flow effortlessly
369 method: 
BAD: Todo: clean my bed
GOOD: My bed is clean at all times

# AI Output
To md files: all steps to be done
To LLM chat: A short summary of what is going on, and the MOST IMPORTANT NEXT STEP
BAD: "Do x,y,z, then a,b,c, then 1,2,3"
Good: "So ..., next step: x,y,z"

# File naming
The project will grow as time goes on, so naming files and folders should be done mindfully
When time matters (like a LOG file):
YYYY-MM-DD_description.[file]

When single version control is desirable like html files:
Name_v2.[file]
Name_v3.[file]

# Folder creation and naming
AI decides if user did not create yet
When multiple files are being edited and it's better to have a version2 folder than file1_v2, file2_v2 etc... for files:
Create subfolder: folder_name[x+1]
In VSCode, the folders are ordered alphabetically, as the number of file grows, it takes time to scroll down to see files
Therefore, the AI or user should organize folder names with this rule: 1_Most_frequent_folder ... 3_less_frequent ... 5_infrequent(like general info and stuff)

# USER BIG 5 personality

# USER MBTI TEST

# LONG TERM GOALS

