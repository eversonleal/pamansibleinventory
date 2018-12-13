# What is it?
An utility to run an Ansible playbook getting SSH user's password from BeyondTrust Privileged Account Management dynamically through the API.
# How to:
Password Safe account settings:

Set environment passwords based on informations from Password Safe
```bash
  export PS_AUTH_KEY= #Auth key generated above\
  export PS_RUN_AS= #Username created\
  export PS_REASON= #Some description\
  export PS_DURATION_MINUTES= #Duration, it musb be longest than the playbook takes to run completelly\
  export PS_SERVERS= #Comma separated server names\
  export PS_BASE_URL= #PAM API base URL\
  export PS_GROUP_NAME= #Group that the playbook expects to run the commands\
```
