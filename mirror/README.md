### GDSC mirror helm/rancher chart

Install of this chart will:
- create a GDSC mirror for one collection

Required configuration values
- Release.name : name of the mirror (i.e. dvmt)
- ingress.hostname : qualified domain name (i.e. sub-domain.domain.tld)
- airflow.config.webserver.base_url : full URL for airflow interface (i.e. https://sub-domain.domain.tld/dvmt/airflow)
