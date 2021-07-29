---
title: "HAProxy with Nginx provisioning"
weight: 2
resources:
    - src: img/flaskAPI-vagrant-ansible.png
      params:
          weight: -100
project_timeframe: June-December
---

<html>
  <body>
    <h4>Automating two-tier infrastructure provisioning through Ansible & Terraform </h4>
  </body>
</html>

---
#### Motivation
For most modern day applications, unpredictable user traffic can be managed by having multiple nodes to serve additional requests. In the case of a web application, we can have two or more web servers behind a load balancer which handles and distributes user requests from the public web. 

In this project, we explore deploying a simple webpage on two nginx web servers. Web requests are load balanced by a HAProxy node to ensure each web node isn't overworked. 

To deploy the application in a reliable and repeatable fashion, we automate the infrastructure provisioning with Terraform while Ansible handles the server set-up as well as installing dependencies. This way we have a phoenix server design with resilience to configuration drift. The whole system will be deployed over AWS cloud.


---

#### Technology stack
AWS | Terraform | Ansible | Nginx | HAProxy
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
<img src="img/aws.png" width="100">  |  <img src="img/terraform.png" width="100">  | <img src="svg/ansible.svg" width="100"> | <img src="img/nginx.png" width="100"> | <img src="img/haproxy.png" width="100"> 

---

View the full project <a href="https://github.com/hideyukikanazawa/haproxy-nginx-deployment" target="_blank" rel="noopener noreferrer">here</a>!