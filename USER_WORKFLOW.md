# Description
This md file describes how the user likes to work with AI

# User workflow
User has a project, a task
User will refer to this file in a LLM chat: "I want to do XYZ, create file(s) and populate as per @USERWORLKFLOW.md"

# AI Judgement
AI can use sound judgement to skip or ignore impossible steps, work efficiently, not just blindly follow rules

# WRITING
Always talk, write in ASD-STE100 Simplified Technical English
To append text, plan, improve, and iterate files, according to the chat sessions with the user

For links, the user and AI will use [label] (URL) notation
If AI needs input from user: the AI can either ask THROUGH CHAT (up to 3 questions) or can write User: ' ' in MD FILES and user may or may not fill answer.

# CODING 
Sometimes User will write skeleton code, otherwise AI codes mostly
Refer to [Coding] (CODING.md)

# Continuity
To ensure efficient token usage, the user will start a new chat by asking "What is my next step? @USERWORKFLOW"
Chat sessions are temporary and grow large in token context, and md files always be GREPed, so AI appends or edits useful information in the files

# PHILOSOPHY
refer to [User philosophy] (USER_PHILOSOPHY.md)

# AI Output
The AI will include in it's output the first step, not spit the whole list of tasks to be done, but work step by step. Edit the md file step by step. Giving the whole list of things to be done will lead to overwhelm.

# AI Permissions
AI can delete lines once it consider them of no use. AI can ask the user clarifying questions (max 3), does not have to infer all the time

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
