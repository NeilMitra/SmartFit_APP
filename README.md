# SmartFit_APP

***WINNER OF THE BEST USE OF VOICEFLOW IN A VOICE ACTIVATED APP AT UOFTHACKS 2020***

Inspiration
Exercise is extremely important and is most effective and healthy when it is evenly applied to all important muscles in your body. However, as students, many of us don't have enough time to finish a complete workout routine that trains every important muscle, and so we split up our exercise routines over several days. However, it can be a hassle to track which muscles you haven't exercised as often, generating friction between a busy student and quality exercise. SmartFit seeks to solve this issue.

What it does
SmartFit is a workout assistant that helps users to become more healthy. It's built upon two main features: logging and recommendation. It tracks your workouts using the Google Assistant and tailors a workout that would benefit the user the most based on an undertrained muscle group, determined by analysis of their previous workouts. SmartFit is also beginner friendly since it offers a tutorial for every different workout. Through SmartFit, anyone can become fit and healthy in a smart way. SmartFit is like a personal trainer that can be accessed at any time and anywhere.

How we built it
We built SmartFit using Voiceflow with calls to Google Sheets’ APIs and deployed on Google Actions to create a fully functional Google Assistant app. Smartfit’s workout logs are stored on Google Sheets and workout recommendations are generated automatically based on past workout data as well as exercise information curated from various professional fitness websites. The recommendation algorithm was designed using smart techniques and formulas within the Google Sheets Platform. JavaScript was used in order to parse user information of logs and prediction of recommendations within Voiceflow. We also made a static website that shows information regarding what SmartFit does.

Challenges we ran into
Since Voiceflow is a relatively new application, we had a hard time finding assistance on certain features that we were unsure about. For example, Voiceflow has the capability to display images using the Card Block or the Display Block, but it was very hard to find help regarding those issues. Due to the lack of documentation, it was very hard to solve problems promptly without halting all progress. Another challenge that we faced was the integration of Google’s Firebase. We ended up using Google Sheets instead of firebase because Google Sheets is already integrated with Voiceflow and is faster and more effective that Firebase in this application.

Accomplishments that we’re proud of
We’re proud of creating a robust voice app using Voiceflow and creating a Google Action usable on Google Assistant.

What we learned
We learned how to use a new application called Voiceflow in order to develop Google Assistant and Amazon Alexa applications without any pre-existing knowledge. We learned how to use Google’s Dialogflow in order to style the front end of SmartFit in the Google Assistant environment. We taught ourselves the intricacies of Google’s API client in order to host SmartFit to any Gmail email address that the user wishes.

What's next for SmartFit
Since SmartFit is on Google’s API platform, sending the app to worldwide alpha testers can be easily accomplished. From the alpha testers’ feedback, more features and user interface improvements will be implemented. The next step for SmartFit is to migrate to a more robust database and increase user customizability via FireBase and MongoDB. The Artificial Intelligence to predict workout recommendations would be implemented using TensorFlow, instead of hardcoded smart algorithms, due to a larger set of users.

After the technology side of things is taken care of, SmartFit can have the opportunity to be implemented into the marketplace. Users can pay for the SmartFit service with different plans in order to have more data analysis and access to tutorials.

CHECK OUT THE DEVPOST: https://devpost.com/software/smartfit-h9kxeg
THE APP: https://creator.voiceflow.com/demo/310536426117027

