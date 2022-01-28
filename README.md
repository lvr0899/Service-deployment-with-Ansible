##Assignment-2##
The task is to implement simple web server for this we need 5 web servers which are created at city cloud network with names devA, devB, devC, haproxy and bastionET2598.Here haproxy is load balancer.
Here we generate site.yaml file which will run through ansible playbook to deploy Haproxy and installs nginx and php in A, B, C servers.
By running the code ansible-playbooks -i hosts site.yaml in the suitable environment the bastion acts as jump host. As written in code we get the reply from A,B,C servers through haproxy and we get the reply as welcome to deva,
welcome to devb, welcome to devc from the server.
Thank you,
Lakshmi Venkata Raghava Sudheer Devanaboina,
19990804-T172.