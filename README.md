# btre_sn
Section#5 Lesson26 : Issue with loading the server page, templates/index.html, templates/about.html
Hello all, I'm recording this snapshot of my code because I have some errors.

1.The server page stops loading though I have my server running "python manage.py runserver"
http://127.0.0.1:8000 shows TemplateDoesNotExist at /
pages/index.html
Request Method:	GET
Request URL:	http://127.0.0.1:8000/
Django Version:	2.1.3
Exception Type:	TemplateDoesNotExist
Exception Value:	
pages/index.html
Exception Location:	/Library/Frameworks/Python.framework/Versions/3.6/lib/python3.6/site-packages/django/template/loader.py in get_template, line 19
Python Executable:	/usr/local/bin/python3
Python Version:	3.6.5
Python Path:	
['/Users/admin/Documents/GitHub/BradTravesty_Media/Dev1/btre_project_sn',
 '/Library/Frameworks/Python.framework/Versions/3.6/lib/python36.zip',
 '/Library/Frameworks/Python.framework/Versions/3.6/lib/python3.6',
 '/Library/Frameworks/Python.framework/Versions/3.6/lib/python3.6/lib-dynload',
 '/Library/Frameworks/Python.framework/Versions/3.6/lib/python3.6/site-packages']
Server time:	Tue, 4 Dec 2018 14:26:25 +0000
"


The server page loaded just fine at the inception of the project but stopped displaying the server 
page at some point as I kept adding code.  

2.After adding the "base.html" unter templates. The 'index.html' and 'about.html' show the following when launched with chrome.
And the source code doesn't display the 'base.html' boilerplate code. 



{% extends 'base.html' %} {% block content %}
Home
{% endblock %}



{% extends 'base.html' %} {% block content %}
About
{% endblock %}





