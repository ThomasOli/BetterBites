![image](https://github.com/user-attachments/assets/ab85ae3d-3621-4ea0-8a42-7eeebd185f5c)
![image](https://github.com/user-attachments/assets/dd0a8cec-eab7-4013-8738-c09542b7554e)
![image](https://github.com/user-attachments/assets/57383663-3ad7-4b28-a690-e2ec5a6647b5)
![image](https://github.com/user-attachments/assets/d5b87051-441e-4638-b206-64db26f8f022)
![image](https://github.com/user-attachments/assets/9a153695-670a-45f9-aefc-d371701ff87b)
![image](https://github.com/user-attachments/assets/257fd304-6eb0-4efa-abfc-f4c6bfee416c)
![image](https://github.com/user-attachments/assets/06185e58-a360-4609-a99a-07200434977c)


##Inspiration
Many people are unaware of the true nutritional content of the foods they consume, particularly when it comes to packaged items. Factors like age, sex, height, weight, and ethnicity also impact how food affects our bodies. Understanding these dynamics is key to making better dietary decisions, but many struggle to find easy access to this information. BetterBites was born out of the desire to help people make more informed, personalized choices about the food they eat, right at their fingertips. A health conscious and green focused approach to eating.

##What it does
BetterBites allows users to scan packaged foods by taking a photo of the nutrition facts and ingredients label. The app processes this image and provides users with clear, digestible information about the food they scanned. This includes nutritional breakdowns, allergen warnings, and insights tailored to the user's profile, helping them make smarter, more informed eating choices.

##How we built it
We built BetterBites using Flutter, leveraging Dart for the app's frontend development. For image recognition and processing, we integrated Google Vision, OpenCV, and Google Cloud APIs. Our backend is powered by Flask and Python, handling data processing and OCR (optical character recognition). We store and manage user data through Firebase Realtime Database, ensuring smooth performance and real-time updates.

##Challenges we ran into
We aimed to implement many advanced features, which ended up overwhelming our initial timeline. Balancing our ambition with realistic goals proved difficult. Additionally, using Android emulators posed technical difficulties, as their low-quality cameras made it hard to scan food labels effectively, slowing down development and testing.

##Accomplishments that we're proud of
We successfully built a visually appealing and user-friendly Flutter app. We integrated OCR technology to accurately extract nutrition facts and ingredients from food labels. Additionally, we scraped nutritional data and carbon footprint metrics, gathering over 50,000 datapoints to enhance user insights. Most importantly, we managed to successfully scan and provide detailed food information to users.

##What we learned
We learned that building scalable, feature-rich apps requires more focus and team coordination than expected. It's important to stay realistic about the scope of a project and focus on perfecting key features rather than overextending. Keeping a clear goal and manageable tasks ultimately drives better outcomes.

##What's next for BetterBites
We aim to enhance our scanning functionality by improving accuracy and speed, especially with lower-quality images. Additionally, we plan to roll out more personalized features, including deeper insights based on users' dietary needs and preferences. Expanding our dataset and incorporating more AI-driven insights are also on the horizon to make BetterBites a must-have tool for conscious eating.
