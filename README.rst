Jenkins 
=======

1. Uruchom jenkins-a:

   ::

     make build_jenkins
     make run_jenkins

2. Otwórz w przeglądarce 127.0.0.1:8080, jeśli zostaniesz poproszony o hasło dla admina, wybierz:

   ::

     cat jenkins/secrets/initialAdminPassword

3. Wybierz *Suggested plugins*.


http://127.0.0.1:9090/
docker ps --all | grep wsb

[root@tester teaching-jenkins]# docker run -t -i jenkins-wsb /bin/bash
_> jeżeli nie działa to:
[root@tester teaching-jenkins]# docker exec -t -i jenkins-wsb /bin/bash
root@28f4780fb76b:/# cat /var/jenkins_home/secrets/initialAdminPassword
b4faae718b7c486184dd13a15aaac757                   
root@28f4780fb76b:/# ^C
root@28f4780fb76b:/#   

