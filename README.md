PROJECT NAME: AI Chatbot using Gemini API.

PROJECT SUMMARY: This project is a simple chatbot built using the Gemini API.It allows users to send messages and receive intelligent responses from Google’s Gemini model.

PROGRAMMING STACK USED: HTML, CSS, JavaScript(Next.js), Gemini API.

SETUP and WORKING:

1) Created a folder Mynodeproject in that imported all the Gemini API, Dependencies, Environment variables.
   commands:
                       npx create-next-app gemini-chatbot
                       cd gemini-chatbot
                       npm install @google/generative-ai dotenv
                       GEMINI_API_KEY=your_gemini_api_key_here
2) Then  create a API router as a separate file in app/api/chat/route.js.
3) Crete a separate file for Frontend Chat UI in app/page.js 
4) And after finishing all the necessary installations. Open the terminal and run the following commands for the output.
   commands:
            cd mynodeproject
            npm run dev
5) When a command is processed it shows 2 links one is Local another one is network.Copy anyone link and paste it in the browser.
6) The Chatbot created by using Gemini API will be shown.
7) Then create a repository in Github. Use the following commands for pushing the project into the Github Repository.
   commands:
           git init
           git add
           git commit -m "first commit"
           git branch -M main
           git remote add origin https://github.com/karthikeyangvk/REV-Intern-
           git push -u origin main
8) Then after pushing the project folder in the Github check whether all the files and folders are pushed into the repository.

ERROR OCCURED:

1) common PowerShell security restriction issue, not a problem with Node.js itself.
2) npm can’t find a package.json file in your project folder. That file is what tells npm which dependencies to install.
3) Next.js rejects names with spaces, because project names must be URL-friendly.
4) Warning: Next.js inferred your workspace root, but it may not be correct.We detected multiple lockfiles... This happens because you accidentally created a Next.js project inside another Next.js project (double nested folders).
5) These are the some errors which i got during installing and running the project.
6) If you get any errors like this use ChatGPT for more improvement for solving errors.












   

             




