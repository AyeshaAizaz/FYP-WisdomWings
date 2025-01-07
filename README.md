# Wisdom Wings: AI-Based Career Counseling Application
## Overview:
Wisdom Wings is a cutting-edge career counseling application designed to empower students and professionals by guiding them toward their ideal career paths. The app leverages Artificial Intelligence (AI) to provide personalized recommendations for courses, undergraduate/graduate programs, and mentors based on individual user profiles, preferences, and skill sets. With an integrated mentorship platform, Wisdom Wings bridges the gap between aspiring learners and experienced professionals, fostering meaningful interactions and informed career decisions.

## Key Features
<h3>1. AI-Powered Recommendations</h3>
<ul>
<li><b>Course Recommendations:</b> Using web-scraped course data from platforms like Coursera, Wisdom Wings recommends the top five courses that align with user interests, skills, and career aspirations.</li>
<li><b>Program Recommendations:</b> Employing advanced algorithms like the YouTube Ranking Algorithm and cosine similarity, the app suggests five undergraduate/graduate programs tailored to each user.</li>
<li><b>Mentor Recommendations:</b> Matches users with five mentors based on skills, location, online status, and mentor reviews to ensure compatibility and effective guidance.</li>
</ul>
<h3>2. Mentorship Platform</h3>
<ul>
<li><b>Mentor-Mentee Matching:</b> Facilitates connections between mentees and mentors based on mutual interests, skills, and goals.</li>
<li><b>Online Status Tracking:</b> Displays real-time online/offline status of mentors, making it easy for mentees to interact at convenient times.</li>
<li><b>Session Scheduling:</b> Users can schedule one-on-one sessions or join broadcast sessions. Time slots are dynamically generated, considering mentor and mentee availability.</li>
</ul>
<h3>3. Dynamic Calendar Integration</h3>
<ul>
<li><b>Highlight Scheduled Sessions:</b> Displays upcoming broadcast sessions and mentor availability on a calendar.</li>
<li><b>Time Slot Generation:</b> Automatically generates available time slots for scheduling, ensuring no conflicts with pre-existing sessions.</li>
<li><b>Current Date Filter:</b> Only future dates are shown, restricting users from selecting past dates.</li>
</ul>
<h3>4. Search Functionality</h3>
<ul>
<li>Allows users to search for mentors or courses stored in the database.</li>
<li>Returns matching results or displays a “No such item found” message if no matches exist.</li>
</ul>
<h3>5. Settings and Profile Management</h3>
<ul>
<li>This module allows the User to manage the account settings and personal information; thus, it encompasses options for profile details updating and customization preferences aimed at improving their experience of app use.</li>
</ul>
<h3>6. Firebase Integration</h3>
<ul>
<li><b>User Profiles:</b> Stores comprehensive user details, including name, gender, interests, skills, qualifications, certifications, job status, and more.</li>
<li><b>Broadcast Sessions:</b> Fetches and manages broadcast session details for mentors and mentees.</li>
<li><b>Real-Time Updates:</b> Ensures seamless data synchronization across the app.</li>
</ul>

## How It Works
<ol>
<li><b>Create a Profile:</b></li>
Fill out your details, including interests, skills, and career goals.
<li><b>Receive Recommendations:</b></li>
AI curates courses, programs, and mentors based on your input.
<li><b>Schedule Sessions:</b></li>
Select available time slots from the calendar.
<li><b>Engage and Learn:</b></li>
Join sessions, interact with mentors, and take notes to enhance your learning experience.
</ol>

## Technical Highlights
<h3>Algorithms and Hosting:</h3>
<li>Hosted AI models on Azure for scalable and reliable performance.</li>
<li>Utilizes AI algorithms like YouTube Ranking and cosine similarity for precise recommendations.</li>
<h3>Database:</h3>
<li>Firebase Realtime Database for storing and retrieving user and session data.</li>
<li>Maintains a hierarchical structure for efficient querying and management of user, mentor, and course details.</li>
<h3>Android App Development:</h3>
<li>Developed in Java for a seamless, user-friendly experience.</li>
<li>Integrated fragments for modular UI navigation, with the first fragment selected by default.</li>

## Screenshots and Visuals

<h3>LOG IN PAGE</h3>
![login](https://github.com/user-attachments/assets/73fc655c-196e-49a7-959e-9c85df22bb8e)

<h3>SIGN UP PAGE</h3>
![signup](https://github.com/user-attachments/assets/927ddc90-72d0-4d9a-8c8e-1d82db34654d)

<h3>USER DETAILS FORM</h3>
![userdetails](https://github.com/user-attachments/assets/d416bc90-d3f4-480e-930e-6203b23a9cf4)

<h3>HOME PAGE</h3>
![homepage](https://github.com/user-attachments/assets/090404f0-d866-4e6a-85a8-5d9dda088848)

<h3MENU PANE</h3>
![menupane](https://github.com/user-attachments/assets/712331fa-27cb-4702-91cd-1179d09f1e2c)

<h3>SETTINGS</h3>
![settings](https://github.com/user-attachments/assets/7d8dd32e-b617-4869-9436-cccb76a8edd1)

<h3>ABOUT US</h3>
![aboutus](https://github.com/user-attachments/assets/814b16d5-7893-40c8-9a7c-026821edb811)

<h3>HELP/FAQ</h3>
![help_faq](https://github.com/user-attachments/assets/94f89b52-d4be-47e1-9e5e-6947de917a12)

<h3>TERMS AND PRIVACY</h3>
![termsandpriv](https://github.com/user-attachments/assets/fe2723b4-7fa5-4af5-b429-4dbec9b4f598)

<h3>NOTIFICATIONS</h3>
![notifications](https://github.com/user-attachments/assets/ea12a6f0-198d-413a-b97a-34009b5e6520)

<h3>COURSE DETAILS</h3>
![coursedetails](https://github.com/user-attachments/assets/e7cf68c8-1036-403e-8bf4-640edeb02ee1)

<h3>SEARCH</h3>
![searchpage](https://github.com/user-attachments/assets/183ffe24-fa07-4ee6-b4d6-3ee43d72d313)

<h3>USER PROFILE</h3>
![userprofile](https://github.com/user-attachments/assets/dfde1c4b-e562-439e-b919-ead2fe3e3aa1)

<h3>CHANGE DISPLAY PICTURE</h3>
![changedisplaypic](https://github.com/user-attachments/assets/5b69cbb1-b3ab-41db-ac9d-398cc012ef88)

<h3>USER VIEWING MENTOR PROFILE</h3>
![userviewingmento](https://github.com/user-attachments/assets/f67b77a5-ad87-499f-8d68-b25f13e2ca03)

<h3>USER REGISTERING 1 ON 1 SESSION</h3>
![registering1on1session](https://github.com/user-attachments/assets/f0f9dcdb-80e9-45c4-8f16-bc3e269e8fbe)

<h3>LOG OUT</h3>
![logoutpage](https://github.com/user-attachments/assets/ab0666fd-4d31-4e82-befe-29572625cb7c)

<h3>MENTOR HOME PAGE</h3>
![mentorhomepage](https://github.com/user-attachments/assets/9ee98671-0e8c-4165-b3c5-014ef720fc77)

<h3>CREATE BROADCAST SESSIONS</h3>
![createbroadcastsession](https://github.com/user-attachments/assets/a4c4bcf8-6fd5-454c-88a0-a43af8df0ef6)

<h3>MENTOR PROFILE</h3>
![mentorprofile](https://github.com/user-attachments/assets/96e73f9d-a249-431f-bbae-f3011a0a2e1d)


## Future Vision
<ol>
<li>Enhance the machine learning model using advanced algorithms with a larger
pool of datasets.</li>
<li>Broaden the scope of features to include interactive tools like video calls and real-time chat to increase user engagement.</li>
<li>Create an analytics dashboard for mentor and mentee to trace progress and
engagement.</li>
<li>Scale system architecture to deliver high performance under maximum loads.</li>
</ol>

