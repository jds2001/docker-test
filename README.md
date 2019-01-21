# Intro

This is a simple 'hello world' docker container built with GitLab CI using the
Docker executor and Docker-in-Docker. In order to use this, you'll need a
private [GitLab](https://gitlab.org) instance (or using gitlab.com with your
own CI/CD runner). The runner must be a docker executor with docker privileged
mode enabled. It is recommended that you understand the security implications
of this decision thoroughly prior to deployment in a production environment.
