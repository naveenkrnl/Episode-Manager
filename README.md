# Episode-Manager
An Episode Manager to manage all your TV Shows right from your screen

I created it to manage the major Shows and series i watch such as Sherlock Holmes, Game of Thrones, etc.
Heres the Home Screen:
<img src='https://raw.githubusercontent.com/naveenkrnl/Episode-Manager/master/screenshot%201.png'>
To download the project right on your computer Download the zip file

Create a virtualenv using
<pre>
virtualenv -p python3 venv</pre>
From Home Directory run command
<pre>
pip install -r requirements.txt</pre>
then run
<pre>
python manage.py collectstatic
python manage.py makemigrations
python manage.py migrate
python manage.py runserver</pre>
