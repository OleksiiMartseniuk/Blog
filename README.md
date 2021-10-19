# Blog
 This blog app is based on django

 ## Current features

* Sending email with Django
* Tag subsystem
* List of recommended articles
* Creating your own tags
* Adding a sitemap
* Adding RSS for Articles
* Search post
* Adding a comments
    

## Snaps of project
Sending email:
![][email_1]
![][email_2]
![][email_3]

Registration:
![][registration]

Tag:
![][tags]

List of recommended articles:
![][recommended_post]


Sitemap:
![][sitemap]

Search post:
![][search_1]
![][search_2]

Comment:
![][comments]

[email_1]:./screenshots/Sending_email.png 
[email_2]: ./screenshots/Sending_email_2.png
[email_3]: ./screenshots/Sending_email_3.png
[tags]: ./screenshots/tags.png
[recommended_post]: ./screenshots/List_recommended_post.png
[sitemap]: ./screenshots/sitemap.png
[search_1]: ./screenshots/search_1.png
[search_2]: ./screenshots/search_2.png
[comments]: ./screenshots/comments.png

# Instructions

1. ## Installations

Make sure to have python version 3 install on you pc or laptop.
<br>
**Clone repository**
<br>
`git_link`

2. ## Installing dependencies

It will install all required dependies in the project.
<br>
`pip install -r requirements.txt`
<br>
Change your values
```python
EMAIL_HOST_USER = os.getenv('EMAIL_HOST_USER')
EMAIL_HOST_PASSWORD = os.getenv('EMAIL_HOST_PASSWORD')
```

2. ## Migrations

Create postgresql database
<br>
To run migrations.
<br>
`python manage.py migrate`

3. ## Create superuser
   
To create super user run.
<br>
`python manage.py createsuperuser`
<br>
After running this command it will ask for username, password. You can access admin panel from
<br>
`localhost:8000/admin/`

4. ## Running locally

To run at localhost. It will run on port 8000 by default.
<br>
`python manage.py runserver`
