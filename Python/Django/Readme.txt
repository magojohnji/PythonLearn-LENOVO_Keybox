WEB���:
	MVC
		Model       View       Controller
		���ݿ�   ģ���ļ�    ҵ����
	
	MTV
		Model    Template     View
		���ݿ�   ģ���ļ�    ҵ����



Django	MTV���

	pip install django
	
	D:\ProgramData\Anaconda3\Scripts
	 
	# ����Django����
	django-admin startproject ���������ơ�
	
		mysite
			- mysite        # �����������������
				- init
				- settings  # �����ļ�
				- url       # URL��Ӧ��ϵ
				- wsgi      # ��ѭWSIG�淶��uwsgi + nginx
			- manage.py     # ����Django����
					- python manage.py 
					- python manage.py startapp xx
					- python manage.py makemigrations
					- python manage.py migrate	
		
	# ����Django����
	python manage.py runserver 127.0.0.1:8001