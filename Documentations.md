
# 1. Preface
Welcome to the Dashboard Project! In order to develop a robust dashboard application, this project combines a React interface with a Django backend. A dynamic and interactive user experience is provided by the frontend, while data management and a RESTful API are handled by the backend.



# 2. Set up
## Prerequisites
* Python (version 3.6 or higher)
* Node.js (version 10 or higher)
* npm (Node.js package manager)


## Django setup - Backend 

* Clone the repository:
  `git clone <repository_url>`
  then
`cd your_project_directory`

* Create a Virtual Environment if required:
  `python -m venv venv`
  then
`source venv/bin/activate`
  On Windows, use 
`venv\Scripts\activate`

* Install Python Dependencies:
  `pip install -r requirements.txt`
* Run Migrations
  `python manage.py migrate`
* Run the Django Development Server
  `python manage.py runserver`

Visit http://localhost:8000/ to ensure the backend is running correctly.

## React setup - Frontend 

* Navigate to the Frontend Directory:
  `cd frontend`
  
* Install Node Modules:
  `npm install`

* Start the React Development Server:
  `npm start`
  
Visit http://localhost:3000/ to see the React app.


# 3. Key Features

## Responsive Design 
Assuring a smooth experience, the dashboard makes use of good design concepts. 

## User Authentication and Personalization
In order to access the dashboard, users must log in using their login credentials.

## Mock API Handling (In Progress)
For demonstration reasons, the application is made to handle datasets stored in an array while the mock API implementation is being completed. Datasets are manually supplied in the lack of a fully complete mock API.



# 4. Assumptions

The initial project approach was affected by a number of assumptions made during the development phase.

* ### Backend-First 

The original idea was to start the frontend design process by concentrating on curating the backend first. Though it can be useful, reflection shows that frontend and backend development are related and should be worked on simultaneously. There were difficulties integrating dummy data for frontend development when a backend-first methodology was the only one used.

* ### Dummy Data for Frontend
  
It was thought that developing frontend applications with fake data would make the process of connecting to a fully functional backend easier in the beginning. Trying to use fake data made it difficult to get a frontend that looked realistic. Even if the backend is still being built, this supposition made clear how crucial it is to have a clear API structure early in the development process.

* ### Implementation of Mock API

The initial belief was that building a mock API for testing would be a simple. Putting in place a mock API had its own set of difficulties, which made reevaluating the original project completion timeline necessary.

 ##### potential Mock API : 
 `https://65d76faa27d9a3bc1d7b0a08.mockapi.io/handle/users`



# 5. Challenges 

* ### Connecting APIs

  #### Description: 
  Django is a potent web framework that offers strong support for Django Rest Framework development of APIs. However, integrating the frontend with the backend API and managing data variables might be a major challenge for developers who are not as familiar with Django and DRF. Troubleshooting frontend-backend interactions, debugging problems with API requests and answers, and comprehending error messages.

  #### Solution: 
  Understanding and implementing appropriate API connections was made easier by a thorough study of the Django REST Framework and examples. Concurrently learning frontend and backend technologies is essential. More efficient communication and coordination between frontend and backend components are facilitated by a well-rounded skill set. Acquiring the knowledge of organizing serializers and views for APIs, as well as making sure URLs are configured correctly to expose the desired data endpoints. API integration can be continuously improved by using an iterative development methodology.

# 6. Learnings 
 I stepped outside of my comfort zone when working on this project's development, especially when it came to using Django for the backend. It turned out to be a difficult but worthwhile experience to integrate APIs with data variables. Delivering a visually pleasing user interface and a useful dashboard was my main goal when I started this project.

Like with any learning experience, I ran into obstacles along the way, particularly while trying to connect the frontend and backend components. I value the chance this project gave me to explore into these technologies, even though there was a learning curve associated with Django and the Django Rest Framework.

Even though the project is not finished yet, the work I have already done shows my present skill set. But the realization that there is always space for development and progress thrills me more. This project demonstrates my capacity to adapt and my commitment to learning by doing.




 
