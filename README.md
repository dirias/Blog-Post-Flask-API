# Table of content
  
# 💻 Blog Post Flask API

Project built as a practice for Flask.

# 📝Description

Blog Post Flask API created to process HTTP requests to CRUD an SQLAlchemy database of users and blog posts.
This project was built with the help of Georgio Tunson under a Flask's course of freeCodeCamp.org. 
For educational porpuses it implements data structures(Linked List, Hash Table, Binary Search Tree, Stacks and Queues).


# 🛠 Technologies

- Python
- Flask
- SQLAlchemy
- Linked List
- Hash Table
- Binary Search Tree
- Stacks and Queues

# 📷 Methods / Routes
## create_user
```
    URL: http://127.0.0.1:5000/user
    Method: POST
    json:
        {
            "name": "Didier",
            "email": "test@email.com",
            "address": "281 Test stree 709723",
            "phone": "8597463215"
        }
```

## get_all_users_descending
```
    URL: http://127.0.0.1:5000/user/descending_id
    Method: GET
```

## get_all_users_ascending
```
    URL: http://127.0.0.1:5000/user/ascending_id
    Method: GET
```

## get_one_user
```
    URL: http://127.0.0.1:5000/user/<user_id>
    Method: GET
    Parameter: user_id
```

## delete_user
```
    URL: http://127.0.0.1:5000/user/<user_id>
    Method: DELETE
    Parameter: user_id
```

## create_blog_post
```
    URL: http://127.0.0.1:5000/blog_post/<user_id>
    Method: POST
    Parameter: user_id
    json:
        {
            "title": "Testing blogpost",
            "body": "This is a blog post"
        }
```
## get_all_blog_posts
```
    URL: http://127.0.0.1:5000/blog_post/<blog_post_id>
    Method: GET
    Parameter: blog_post_id
```

## get_numeric_post_bodies
```
    URL: http://127.0.0.1:5000/blog_post/numeric_body
    Method: GET
```

## delete_last_10
```
    URL: http://127.0.0.1:5000/blog_post/delete_last_10
    Method: DELETE
```


# Resources

## 📑Course 
🔗 https://www.freecodecamp.org/news/learn-data-structures-flask-api-python/

# 👨‍💻 Author 
Didier Irias Méndez <br>
Software Developer - 🔗[Linkedin](https://www.linkedin.com/in/didier-irias-m%C3%A9ndez-4ba593147/) 