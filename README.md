## This Repository is my Internship- MERN Stack project done at [NullClass](https://nullclass.com/).

[Click here](https://stack-overflow-clone-namasivaayam-l.netlify.app/), this will take you to my live website.

My first task in my internship was to clone the stackoverflow website, within **15 days**.

I **started** my Internship on **January 15 of 2023**.

I **completed** cloning the required website on **May 31 of 2022**.

Once I did that, I got **3 additional tasks** to complete within the next **15 days**.

### Tasks Assigned

1. Integrate a chatbot feature where users can ask their questions directly to the chatbot.It should answer all programing related questions.Authenticate with OTP before asking questions.
2. Create subscriptions using a payment gateway (like stripe, razorpay) to post questions in stackoverflow.**Testcase**: Free Plan can post only 1 question a day, silver plan will be ₹100/month which can post 5 questions a day and gold plan can post unlimited questions and priced at ₹1000/month.
3. Create a social media community where people can share images, and videos and get likes and shares and also be able to add friends and remove friends.**Testcase:** Users can share their programming experience here using text, photos, and videos which can be viewed by others. Users can search, like, unlike, remove, add their friends.

### Tasks Completed

1. I have implemented email authentication using nodemailer module in node.js.
2. The user must enter his registered email id and enter the OTP received in his email inorder to use the chatbot.
3. I added a chatbot that fetches the top answers for your question from https://api.stackexchange.com/
4. I have used react-simple-chatbot module to implement the chatbot in this website.
5. In this website there are 3 plans to opt for.
   1. Free Plan - Price: 0 rupees - 1 Question/Day.
   2. Silver Plan - Price: 100 rupees/Month - 5 Questions/Day.
   3. Gold Plan -Price: 1000 rupees/Year - Unlimited Questions/Day.
6. I have used stripe payment gateway to complete all the transactions regarding the subscription plans.
7. In Social Media page, Users can
   1. Post.
   2. Follow.
   3. UnFollow.
   4. Hide.
   5. Post (Video, Photo , Text).
   6. Like.
   7. Remove Like.
   8. Comment.
   9. Delete Post/Comment

![1674766637894](https://file+.vscode-resource.vscode-cdn.net/home/namachu/Documents/Web%20Dev/stack-overflow-clone/image/README/1674766637894.png)

### Features of this Website

1. Once the user sign's in or log's in to the website they will be provided with token and it will expire in the next 24 hours, after that the user will be logged out automatically. They need to log back in to continue using the site.
2. Users are able to:
   1. View a question
   2. Ask a question.
   3. Answer a question.
   4. Delete a question.
   5. Up/Down vote.
   6. Share.
3. Users can opt for any of the two premium subscription plans offered. Free plan is applied by default for every user.
4. Users can share their coding videos, code snippets, pics of code in the social media tab.
5. And they can make use of the chatbot to clear doubts regarding programming.

### Technology Used

1. React.js
2. Node.js
3. Express.js
4. MongoDB Atlas/Compass
5. Redux
6. React-Router-Dom-V6
7. Material UI Icons.
8. React Simple Chatbot
9. Nodemailer
10. Mongoose

### Hosting Details

##### Frontend

1. I created an optimized build using npm run build command. And Pushed it to github repo.
2. I used [netlify](app.netlify.com) site to deploy my frontend.
3. I  connected my github account to netlify and used the optimized build for deployment.

##### Backend

1. I deployed the backend in [onrender](onrender.com).
2. I have used **MongoDB** **Atlas** for Database.

### Images

![1674342484144](image/README/1674342484144.png)

![1674342644090](image/README/1674342644090.png)

![1674342495090](image/README/1674342495090.png)

![1674342075579](image/README/1674342075579.png)          ![1674342181884](image/README/1674342181884.png)

![1674343695563](image/README/1674343695563.png)          ![1674343757188](image/README/1674343757188.png)

![1674342681740](image/README/1674342681740.png)

![1674342691282](image/README/1674342691282.png)

### Installation Procedure

`cd client && npm i --force`

`cd server && npm i`

`cd client && npm start`

`cd server && npm start`

### Future Plans

1. Planned to Integrate Chat GPT in the existing chatbot.
2. Perform OTP Verification via mobile number.
