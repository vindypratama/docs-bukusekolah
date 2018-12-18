###########
Konfigurasi
###########

JSON File Generator
===================

* Jalankan perintah berikut untuk menghasilkan JSON file:

  - ``domainurl/home/generateJson2013/1-6/1``
  - ``domainurl/home/generateJsonAllTeks/1-6``
  - ``domainurl/home/generateJsonAllTeksKonfirmasi/1-6``

  - ``domainurl/home/generateJson2013/7-9/1``
  - ``domainurl/home/generateJson2006/7-9``
  - ``domainurl/home/generateJsonAllTeks/7-9``
  - ``domainurl/home/generateJsonAllTeksKonfirmasi/7-9``

  - ``domainurl/home/generateJson2013/10-12/1``
  - ``domainurl/home/generateJson2006/10-12``
  - ``domainurl/home/generateJsonPeminatan/10-12``
  - ``domainurl/home/generateJsonAllTeks/10-12``
  - ``domainurl/home/generateJsonAllTeksKonfirmasi/10-12``

Cron Job
========

* Create crontab for send invoice to customer everyday at 5 a.m, within this url's :

  - ``domainurl/others/autosendmail/sendfaktur``

* Create crontab for send mail using swiftmailer spool feature, within this url's :
  
  - ``domainurl/processEmailSpool``
