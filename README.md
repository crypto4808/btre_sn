# btre_sn
Section#5 Lesson26 : Issue with loading the server page, templates/index.html, templates/about.html
Hello all, I'm recording this snapshot of my code because I have some errors.

Firstly, the server page stops loading though I have my server running "python manage.py runserver"
After adding the "base.html" unter templates. The 'index.html' and 'about.html' show the following when launched with chrome.
And the source code doesn't display the 'base.html' boilerplate code. 

{% extends 'base.html' %} {% block content %}
Home
{% endblock %}


My server ran just fine the inception of the project but stopped displaying the server 
page at some point of adding code as I went along with the lectures. 
