Role Name
=========

A brief description of the role goes here.

Notes: 
AWS Secrete key has been removed from the variable file and tasks. You need to have a look at the image 5.5 and add the two lines in the task. these two lines will be secret key and access key. The task can contain the secret and access keys like shown below.

aws_access_key: "{{ aws_access_key }}"

aws_secret_key: "{{ aws_secret_key }}"

