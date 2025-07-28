## GDSC mirror helm/rancher chart  

Install of this chart will:  
- create a GDSC mirror for one collection  

#### Required configuration values  
- Release.name : name of the mirror (i.e. dvmt)  
- ingress.hostname : qualified domain name (i.e. sub-domain.domain.tld)  
- airflow.config.webserver.base_url : full URL for airflow interface (i.e. https://sub-domain.domain.tld/dvmt/airflow)  

#### Note: you will need to configure secrets for:  
- certificate for ingress: r1-dev  
- docker credential: docker-hub-cred  
- gdsc secrets: postgis  
- git secret: ssh-git-secret  

see https://github.com/Geospatial-Digital-Special-Collections/helm > mirror/secrets for exmaples.  