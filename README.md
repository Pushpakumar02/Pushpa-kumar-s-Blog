
# My Flask Blog

This is a simple Flask blog application with user authentication, CRUD operations for blog posts, and comment functionality. Users can register, log in, create, edit, and delete their blog posts. They can also comment on blog posts.

## Installation

To run this application locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/Pushpakumar02/Pushpa-kumar-s-Blog.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Pushpa-kumar-s-Blog
   ```

3. Install the required dependencies using pip:

   ```bash
   pip install -r requirements.txt
   ```

4. Set up environment variables for your email and password:

   ```bash
   export MY_MAIL=your_email@gmail.com
   export PASSWORD=your_password
   ```

5. Run the application:

   ```bash
   python main.py
   ```

6. Open your web browser and go to [http://127.0.0.1:5000](http://127.0.0.1:5000) to view the application.

## Dependencies

- Bootstrap_Flask==2.3.3
- Flask_CKEditor==0.5.1
- Flask_Login==0.6.3
- Flask-Gravatar==0.5.0
- Flask_WTF==1.2.1
- WTForms==3.0.1
- Werkzeug==3.0.0
- Flask==2.3.2
- flask_sqlalchemy==3.1.1
- SQLAlchemy==2.0.25
- gunicorn==21.2.0
- psycopg2-binary==2.9.9

## Live Version

You can find a live version of this application deployed [here](https://pushpa-kumar-s-blog.onrender.com/).

## For Users

To interact with the blog, users need to log in to comment on blog posts. If you don't have an account, you can register. Once registered or logged in, you can comment on any blog post.

## Credits

This project is part of the 100 Days of Code course by Angela Yu on Udemy. You can find Angela Yu's course repository [here](https://github.com/appbrewery/100-days-of-python).


