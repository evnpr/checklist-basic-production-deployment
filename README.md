# checklist-basic-production-deployment

This repository contains information on checklist production deployment that any team/organisation should consider before push their system into production.

## List 

* version control system setup (e.g Git) and repository
* readme for documentation setup and deployment
* monitoring and alerting system (4 golden signals)
    * latency [e.g newrelic]
    * traffic [e.g newrelic]
    * saturation [e.g grafana]
    * error [e.g newrelic, sentry, pinger, fabric (for mobile)]
* (centralised) logging system
* ENV or dynamic configuration
* database and storage backup mechanism
* controllable domain (not IP or 3rd party domain) : especially if being used by external system
* setup auto deployment (with auto testing as well)
* load balancer
* force update mechanism (mobile)
* auto-logout mechanism (mobile)
* push notification handler (mobile)
* controllable and dynamic config for base_url, etc (mobile)
* basic analytics (GA especially for web)
* setup mechanism for changes on deployment (e.g migration db mechanism)
* make sure the system can handle load for upcoming predicted throughput


