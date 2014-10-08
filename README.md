proyecto
========

preimera parte 
Microsoft Windows [Versión 6.2.9200]
(c) 2012 Microsoft Corporation. Todos los derechos reservados.

C:\Users\MONI>cd..

C:\Users>cd..

C:\>f;
"f" no se reconoce como un comando interno o externo,
programa o archivo por lotes ejecutable.

C:\>f:

F:\>mkdir proyecto

F:\>cd proyecto

F:\proyecto>django-admi startproject tribia
"django-admi" no se reconoce como un comando interno o externo,
programa o archivo por lotes ejecutable.

F:\proyecto>django-admi startproject tribia
"django-admi" no se reconoce como un comando interno o externo,
programa o archivo por lotes ejecutable.

F:\proyecto>django-admi.exe startproject tribia
"django-admi.exe" no se reconoce como un comando interno o externo,
programa o archivo por lotes ejecutable.

F:\proyecto>django-admin startproject tribia

F:\proyecto>cd tribia

F:\proyecto\tribia>python manage.py runserver
Performing system checks...

System check identified no issues (0 silenced).

You have unapplied migrations; your app may not work properly until they are app
lied.
Run 'python manage.py migrate' to apply them.
October 08, 2014 - 02:08:39
Django version 1.7, using settings 'tribia.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CTRL-BREAK.
[08/Oct/2014 02:31:03] "GET /admin/ HTTP/1.1" 500 148359

Microsoft Windows [Versión 6.2.9200]
(c) 2012 Microsoft Corporation. Todos los derechos reservados.

C:\Users\MONI>cd..

C:\Users>cd
C:\Users

C:\Users>cd..

C:\>f:

F:\>cd practica

F:\practica>cd ..

F:\>cd proyecto

F:\proyecto>cd tribia

F:\proyecto\tribia>django-admin.py startapp
"django-admin.py" no se reconoce como un comando interno o externo,
programa o archivo por lotes ejecutable.

F:\proyecto\tribia>mkdir app

F:\proyecto\tribia>cd app

F:\proyecto\tribia\app>django-admin.py startaapp usuario
"django-admin.py" no se reconoce como un comando interno o externo,
programa o archivo por lotes ejecutable.

F:\proyecto\tribia\app>django-admin  startaapp usuario
Unknown command: 'startaapp'
Type 'django-admin-script.py help' for usage.

F:\proyecto\tribia\app>django-admin  startapp usuario

F:\proyecto\tribia\app>django-admin  startapp inicio

F:\proyecto\tribia\app>python manage.py syncdb
python: can't open file 'manage.py': [Errno 2] No such file or directory

F:\proyecto\tribia\app>cd..

F:\proyecto\tribia>cd..

F:\proyecto>dir
 El volumen de la unidad F es Nuevo vol
 El número de serie del volumen es: 5A1A-8F49

 Directorio de F:\proyecto

08/10/2014  02:07 a.m.    <DIR>          .
08/10/2014  02:07 a.m.    <DIR>          ..
08/10/2014  02:36 a.m.    <DIR>          tribia
               0 archivos              0 bytes
               3 dirs  233.039.794.176 bytes libres

F:\proyecto>cd tribia

F:\proyecto\tribia>dir
 El volumen de la unidad F es Nuevo vol
 El número de serie del volumen es: 5A1A-8F49

 Directorio de F:\proyecto\tribia

08/10/2014  02:36 a.m.    <DIR>          .
08/10/2014  02:36 a.m.    <DIR>          ..
08/10/2014  02:38 a.m.    <DIR>          app
08/10/2014  02:08 a.m.             3.072 db.sqlite3
08/10/2014  02:07 a.m.               249 manage.py
08/10/2014  02:08 a.m.    <DIR>          tribia
               2 archivos          3.321 bytes
               4 dirs  233.039.794.176 bytes libres

F:\proyecto\tribia>python manage.py runserver
Performing system checks...

System check identified no issues (0 silenced).

You have unapplied migrations; your app may not work properly until they are app
lied.
Run 'python manage.py migrate' to apply them.
October 08, 2014 - 02:40:53
Django version 1.7, using settings 'tribia.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CTRL-BREAK.

