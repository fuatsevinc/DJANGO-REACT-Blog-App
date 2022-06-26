# DJANGO-REACT-Blog-App
## Django-React-Blog

### This is a “Blogging Platform” which gives all general features a blog should have.

### The backend is completely build on Django using Django Rest Framework, while the frontend is completed using ReactJS.

- Features
- Login/Registration
- Minimal Design
- Create/Edit/Delete Your Posts
- User Profile
- Comment Enable
- Admin Panel
- Create/View/Edit/Delete A User
- Create/View/Edit/Delete A Post By Any User
- View/Edit/Delete All Comments In The Blog
- View/Edit/Delete All Comments To A Specific Post
- Publish/Unpublish A Post
- Backend Setup
- Clone this repository: git clone https://github.com/fuatsevinc/DJANGO-REACT-Blog-App.git
- Change the current directory to backend folder: cd ./Django-React-Blog/backend/.
- Create a virutal environment and install all backend dependencies with pipenv: pipenv install.
- Start the virtual environment: pipenv shell.
- Change the working directory to blog_backend which contains the manage.py file: cd ./blog_backend.
- Run python manage.py makemigrations.
- Run python manage.py migrate.
- Create a superuser: python manage.py createsuperuser
- Run the server: python manage.py runserver.
# Frontend Setup
- Navigate the current working directory to blog_frontend: cd ./Django-React-Blog/frontend/blog_frontend/.
- Install the all frontend dependencies using npm: npm install.
- Run the server: npm start.
- Creating The First Post
- Make sure that both Backend and Frontend Servers are running.
- Open your browser and navigate to localhost:3000.
- `Go To http://localhost:3000/login/.`
- Login with the superuser credentials created while setting up the Backend (Step: 8)
- Navigate To Dashboard -> Create New Post (http://localhost:3000/dashboard/create-new-post).
- Fill the form to create a new post and then Submit it.
- The submitted post will not appear on the homescreen unless and until the admin approves it.
- To approve the post, go to Dashboard -> Admin Panel -> View All Posts and then click on Edit Button.
- Check the checkbox labelled Published and then submit.
- After the post gets published, it will be displayed on the homepage of the blog (localhost:3000).
- Note: Once the post gets published, the user can only edit the post from the Dashboard, however, the admin still can edit/delete the post - from the Admin Panel
- Backend API Documentation
- API Documentation is generated using the default tool provided by Django Rest Framework.

### View The API documentation
- Make sure that the Backend Server is running.
- Navigate to the localhost:8000/docs/

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Timmana&size=30&duration=6000&color=F74747&center=true&vCenter=true&lines=%F0%9F%94%97+Connect+with+me)](https://git.io/typing-svg)
<p align="left">
<a href="https://www.linkedin.com/in/fuat-sevin%C3%A7-6a7969217/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="fuat sevinc" height="30" width="40" /></a>
</p>
<p align="left">
- This is <a href="https://fuatsevinc.github.io/my_portfolio/index.html" target="_blank">My Portfolio Website</a>
</p>
