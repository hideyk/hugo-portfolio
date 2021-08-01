---
title: "FlaskAPI provisioning with Vagrant & Ansible"
weight: 800
project_timeframe: Feb 2021
---

<html>
  <body>
    <h4>Provisioning FlaskAPI and PostgreSQL with Vagrant and Ansible</h4>
  </body>
</html>

<br>
View the full project <a href="https://github.com/hideyukikanazawa/flask-API-provisioning" target="_blank" rel="noopener noreferrer">here</a>!

---
#### Motivation
Inspiration behind this project was fueled by two main areas; first is the desire to provide a simple workflow which enables developers, business analysts & testers to run their API calls against the same pre-alpha/alpha flask API server and be aligned with their UAT (User Acceptance Testing) standards. The other area that motivated this project was to build familiarity with provisioning software (Vagrant/Oracle VM Box) and configuration management tools (Ansible).

The project entails automating provisioning of a FlaskAPI service with a PostgreSQL database through a simple CLI command: `vagrant up`.
 of Virtual Machines using `Oracle VirtualBox` with a base Ubuntu Xenial image. `Ansible` will proceed to set-up and configure `FlaskAPI` on one VM (front-end) and `PostgreSQL` DB on the other. The flaskAPI endpoint would then be exposed to the public using the `ngrok` public hosting service through `vagrant share` command. 

One way to improve the workflow would be to introduce a CI/CD pipeline with robust test cases. Connecting the Github webhook with Jenkins or CircleCI, we could take one step further and automate build, testing and deployment upon any repository push by the developer team. 

---

#### Technology stack
Ubuntu | Vagrant | Ansible | Python | PostgreSQL | ngrok
:---:|:---:|:---:|:---:|:---:|:---:
<img src="img/ubuntu.png" width="100">  |  <img src="img/vagrant.png" width="100">  | <img src="svg/ansible.svg" width="100"> | <img src="img/python.png" width="100"> | <img src="img/postgres.png" width="100"> | <img src="img/ngrok.png" width="100">

---

View the full project <a href="https://github.com/hideyukikanazawa/flask-API-provisioning" target="_blank" rel="noopener noreferrer">here</a>!