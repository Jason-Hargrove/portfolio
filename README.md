# Jason Hargrove - Portfolio

Hey there! 👋 I'm Jason, a visual artist turned full-stack developer. I'm passionate about blending creativity and technology to craft unique digital experiences. From designing sleek user interfaces to streamlining processes with automation, I'm all about turning challenges into intuitive solutions.

With a continuous thirst for learning and a knack for creative problem-solving, I'm committed to delivering impactful results that exceed expectations. My background as a visual artist gives me a unique perspective in software engineering, allowing me to approach projects with creativity and innovation.

# This Is Me

![jasonhargroveart.com](https://images.squarespace-cdn.com/content/v1/57902faa59cc68a958c59c03/1470089724453-O1WN2E2YQHVPXJVRD7YQ/About+The+Artist-1.jpg?format=1000w)

## How to Run Locally

To run this application locally, follow these steps:

1. **Install Dependencies:** Navigate to the project directory in your terminal and run:

   ```zsh
   npm install
   ```

2. **Start the Server** Start the Express server by running:

   ```zsh
   npm start
   ```

   This will start the server, and it will be accessible at http://localhost:3000 by default.

## Heroku

To push your updated project to Heroku, follow these steps:

1. **Login to Heroku:** If you're not already logged in, open your terminal and run:

   ```zsh
   heroku login
   ```

2. **Add Heroku Remote (if not already added):** If the Heroku remote isn't linked to your project, add it by running:

   ```zsh
   heroku git:remote -a <your-heroku-app-name>
   ```

3. **Push to Heroku:** Once you've committed your changes to GitHub and your Heroku remote is set, push the changes to Heroku by running:

   ```zsh
   git push heroku main
   ```

4. **Check Logs:** After pushing, you can check the logs to make sure the deployment was successful by running:

   ```zsh
   heroku logs --tail
   ```

   This should deploy your updated code to the existing Heroku app.

# Links

[**This Project on Heroku**](https://jason-hargrove-portfolio-5abbf0f5084c.herokuapp.com/)

[**My Personal Website**](http://www.jasonhargroveart.com/)
