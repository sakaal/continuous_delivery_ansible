# Continuous Delivery

This is a configuration management database (CMDB)
for tracking configuration items (CIs) related to continuous delivery (CD)
of web applications developed using the
[service platform](https://github.com/sakaal/service_platform_ansible/).

## Current implementation

This Git repository contains Ansible playbooks to be deployed on
a continuous integration node that controls the delivery of web applications.
The controller may execute these playbooks in order to automatically deploy
various components at different stages of the delivery pipeline.

* See the
  [application portfolio](https://github.com/sakaal/service_platform_ansible/wiki/Application-portfolio)
  for an exhaustive list of the applied specifications and implementations.

This part of the implementation deals mostly with:

Platform component                    | Supported alternatives
------------------------------------- | ----------------------
Configuration management              | Ansible
Software artifact management          | Sonatype Nexus OSS
Continuous Integration (CI)           | Jenkins CI
Application server                    | WildFly
Release management                    | Apache Maven

## Continual improvement

Please feel free to submit your proposals for specific improvements
to this process module, its solution alternatives, or configuration items,
as pull requests or issues to this repository.

Let the [wiki](https://github.com/sakaal/service_platform_ansible/wiki)
serve as a part of the service knowledge management system (SKMS).

You may fork this module and adapt it for your needs (even for commercial use).
Please refer to the enclosed license documents for details.

Thank you for your interest and support to peer-to-peer service management.
