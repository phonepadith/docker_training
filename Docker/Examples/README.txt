ตั้งแต่ Chapter8 - Chapter16 ຜູ້ອ່ານຈະໄດ້ Code ສຳລັບການເຮັດ Practice Workshop ເພື່ອຄວາມສະດວກບໍ່ຕ້ອງ Code ເອງ

Chapter8
docker101/
.
├── Dockerfile
└── main.py

Chapter9
small_image/
.
├── Dockerfile
└── Dockerfile_edit 

web_dock/
.
├── docker-compose.yml
└── server/
    ├── Dockerfile
    ├── index.html
    └── server.py

port_dock/
.
├── docker-compose.yml
└── .env

Chapter10
httpd_dock/
.
├── docker-compose.yml
└── html/
    └── index.html

nginx_dock/
.
├── docker-compose.yml
└── static-html/
    └── index.html

lemp_dock/
.
├── docker-compose.yml
├── docker-compose_edit.yml 
├── html/
│   ├── index.php
│   └── index_edit.php 
├── mariadb/
│   ├── backup/
│   ├── data/
│   └── initdb/
│       └── titanic.sql
├── nginx
│   ├── conf/
│   │   └── nginx.conf
│   └── conf.d/
│       └── default.conf
└── php/
    └── Dockerfile

Chapter11
nginx_proxy_dock/
.
├── docker-compose.yml
└── docker-compose_edit.yml 

website1/
.
├── docker-compose.yml
├── docker-compose_edit.yml 
├── docker-compose_edit2.yml 
├── docker-compose_edit3.yml 
├── html/
│   ├── index.php
│   └── index_edit.php #นำ Code 
├── mariadb/
│   ├── backup/
│   ├── data/
│   └── initdb/
│       └── titanic.sql
├── nginx/
│   ├── conf/
│   │   └── nginx.conf
│   └── conf.d/
│       └── default.conf
└── php/
    └── Dockerfile

website2/
.
├── docker-compose.yml
├── docker-compose_edit.yml 
├── docker-compose_edit2.yml
├── html/
│   ├── index.php
│   └── index_edit.php 
├── mariadb/
│   ├── backup/
│   ├── data/
│   └── initdb/
│       └── titanic.sql
├── nginx/
│   ├── conf/
│   │   └── nginx.conf
│   └── conf.d/
│       └── default.conf
└── php/
    └── Dockerfile

Chapter12
mq_dock/
.
└── docker-compose.yml

register_gateway_dock/
.
├── docker-compose.yml
└── python/
    ├── Dockerfile
    ├── api.py
    └── requirements.txt

student_dock/
.
├── docker-compose.yml
├── mariadb/
│   ├── backup/
│   ├── data/
│   └── initdb/
│       └── devops_db.sql
└── python/
    ├── Dockerfile
    ├── requirements.txt
    └── rpc.py

enroll_dock/
.
├── docker-compose.yml
├── mariadb/
│   ├── backup/
│   ├── data/
│   └── initdb/
│       └── devops_db.sql
└── python/
    ├── Dockerfile
    ├── requirements.txt
    └── rpc.py

email_dock/
.
├── docker-compose.yml
└── python/
    ├── Dockerfile
    ├── requirements.txt
    └── rpc.py

Chapter13
kong_dock/
.
├── docker-compose.yml
└── prometheus.yml

grafana_dock/
.
└── docker-compose.yml

Chapter14
otp_dock/
.
├── docker-compose.yml
└── python/
    ├── Dockerfile
    ├── requirements.txt
    └── rpc.py

send_email_otp_dock/
.
├── docker-compose.yml
└── python/
    ├── Dockerfile
    ├── requirements.txt
    └── rpc.py

otp_gateway_dock/
.
├── docker-compose.yml
└── python/
    ├── Dockerfile
    ├── api.py
    └── requirements.txt

session_server_dock/
.
└── docker-compose.yml

register_ui_dock/
.
├── docker-compose.yml
└── python/
    ├── Dockerfile
    ├── model.py
    ├── requirements.txt
    ├── templates/
    │   ├── authen.html
    │   ├── otp.html
    │   └── reg.html
    └── ui.py

Chapter15
register_ui_dock/
.
├── docker-compose.yml
├── docker-compose_edit.yml 
└── python/
    ├── Dockerfile
    ├── model.py
    ├── requirements.txt
    ├── requirements_edit.txt
    ├── templates/
    │   ├── authen.html
    │   ├── authen_edit.html 
    │   ├── otp.html
    │   ├── otp_edit.html
    │   ├── otp_edit2.html
    │   ├── reg.html
    │   └── reg_edit.html 
    ├── ui.py
    ├── ui_edit.py 
    └── ui_edit2.py 

register_gateway_dock/
.
├── docker-compose.yml
├── docker-compose_edit.yml 
    ├── Dockerfile
    ├── api.py
    ├── api_edit.py #นำ Code 
    └── requirements.txt

otp_gateway_dock/
.
├── docker-compose.yml
├── docker-compose_edit.yml 
└── python/
    ├── Dockerfile
    ├── api.py
    ├── api_edit.py 
    └── requirements.txt

student_dock/
.
├── docker-compose.yml
├── docker-compose_edit.yml 
├── mariadb/
│   ├── backup/
│   ├── data/
│   └── initdb/
│       └── devops_db.sql
└── python/
    ├── Dockerfile
    ├── Dockerfile_edit 
    ├── requirements.txt
    └── rpc.py

enroll_dock/
.
├── docker-compose.yml
├── docker-compose_edit.yml 
├── mariadb/
│   ├── backup/
│   ├── data/
│   └── initdb/
│       └── devops_db.sql
└── python/
    ├── Dockerfile
    ├── Dockerfile_edit 
    ├── requirements.txt
    └── rpc.py

email_dock/
.
├── docker-compose.yml
├── docker-compose_edit.yml 
└── python/
    ├── Dockerfile
    ├── Dockerfile_edit
    ├── requirements.txt
    └── rpc.py

otp_dock/
.
├── docker-compose.yml
├── docker-compose_edit.yml 
    ├── Dockerfile
    ├── Dockerfile_edit 
    ├── requirements.txt
    └── rpc.py

send_email_otp_dock/
.
├── docker-compose.yml
├── docker-compose_edit.yml 
└── python/
    ├── Dockerfile
    ├── Dockerfile_edit 
    ├── requirements.txt
    └── rpc.py

mq_dock/
.
├── docker-compose.yml
└── docker-compose_edit.yml 

Chapter16
test_project/
.
├── app.py
├── conftest.py
├── pytest.ini
├── src/
│   ├── __init__.py
│   └── math.py
└── tests/
    └── unit_tests
        └── math_test.py

otp_dock/
.
├── docker-compose.yml
├── .gitlab-ci.yml
└── python/
    ├── Dockerfile
    ├── conftest.py
    ├── pytest.ini
    ├── requirements.txt
    ├── rpc.py
    ├── src/
    │   ├── __init__.py
    │   └── otp.py
    ├── tests/
    │   └── unit_tests/
    │       └── otp_test.py
    └── .env

gitlab_dock/
.
└── docker-compose.yml

runner_dock/
.
├── docker-compose.yml
└── runner_registry.sh
