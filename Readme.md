# Blog API using Django rest framework
## Getting started

Steps:
1. Clone/pull/download this repository
2. Create a virtualenv with `virtualenv env` and install dependencies with `pip install -r requirements.txt`
3. Run Command `python manage.py runserver`


APIs:
1: Post `http://127.0.0.1:8000/posts`
2: Post Detail `http://127.0.0.1:8000/posts/<pk>`
3: Comment `http://127.0.0.1:8000/comments`
4: Comment Detail `http://127.0.0.1:8000/comments/<pk>`
5: Categories `http://127.0.0.1:8000/categories/`

Json Format:
` {
        "id": 1,
        "title": "",
        "body": "",
        "owner": "",
        "comments": [
            
        ],
        "categories": []
    }
`