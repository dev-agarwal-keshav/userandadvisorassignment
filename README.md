# userandadvisorassignment

After opening the file run: 
<br/>pip install -r requirements.txt
<br/>python manage.py runserver
<br/>
<br/>On the website open the link:
<br/>127.0.0.1:8000/admin/advisor/ ---to add an advisor using admin(POST- name: <advisor_name>, photo:<photo_url>)
<br/>127.0.0.1:8000/user/register/ ---to register a new user(POST- name:<user_name>, email:<user_email>, password:<user_password>)
<br/>127.0.0.1:8000/user/login/ ---- to login as an already registered user(POST- email:<user_email>, password:<user_password>)
<br/>127.0.0.1:8000/user/<int:user_id>/advisor ----to get a list of all advisors
<br/>127.0.0.1:8000/user/<int:user_id>/advisor/<int:advisor_id>/ ---to book an advisor(POST- date:<date_as_string>)
<br/>127.0.0.1:8000/user/<int:user_id>/advisor/booking/ ---to get a list of all booking of user=user_id
