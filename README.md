<h1>README for Virtual Assistant API</h1>
Introduction
The Virtual Assistant API is designed to provide users with personalized responses based on their input and the day of the week. This API acts as the foundation for a virtual assistant app, delivering a friendly greeting and a cheerful message to enhance the user's experience.

<h2>API Details</h2>
Endpoint
GET /assistant/greet?name=<user_name>

Request Parameters
name (required): The user's name, sent as a query parameter.
Response Format
A JSON object containing:

A personalized welcome message using the provided name.
A cheerful message depending on the current day of the week.
Responses
For Monday:
{
  "welcomeMessage": "Hello, John! Welcome to our assistant app!",
  "dayMessage": "Happy Monday! Start your week with energy!"
}
For Friday:
{
  "welcomeMessage": "Hello, John! Welcome to our assistant app!",
  "dayMessage": "It's Friday! The weekend is near!"
}
For Other Days:
{
  "welcomeMessage": "Hello, John! Welcome to our assistant app!",
  "dayMessage": "Have a wonderful day!"
}
How to Fork and Set Up Your Repository
1. Fork the Repository
Go to the repository on GitHub and click the Fork button at the top right of the page.
This will create a copy of the repository in your own GitHub account.
2. Clone the Repository
Once the repository is forked, click the Clone button and copy the link (HTTPS or SSH).
Open your terminal/command prompt and run:
git clone <repository_url>
Replace <repository_url> with the link you copied from your GitHub.
3. Install Dependencies
Navigate to the cloned directory:
cd <repository_folder>
Install all necessary dependencies mentioned in the package.json file:
npm install
Submission Instructions
After completing the task, commit and push your changes to your GitHub repository:
git add .
git commit -m "Completed Virtual Assistant API task"
git push origin main
Submit the GitHub repository link on the assignment page.
The link should follow this format:
https://github.com/<your_username>/<repository_name>
Example Submission
If your GitHub username is johnDoe and your repository is named virtual-assistant-api, the submission link would be:
https://github.com/johnDoe/virtual-assistant-api

