Prerequisites:
* SSL certs signed. We assume SSL certs ananware.systems.key, ananware.systems.crt, and ananware.systems.pem was created and stored securely. Certs were signed by https://gethttpsforfree.com

Remember to add your .gitignore so the certs are not uploaded to github.

* Deploy the certs using k8s secrets using the script create-cert-secret.sh. 

* If you haven't done so, create a domain name (using Google Domains, GoDaddy etc)

* Create and deploy your own image using build.sh

* Update values.yaml and deploy the Chart.
