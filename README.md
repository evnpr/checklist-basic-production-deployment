# Basic Checklist Production Deployment

This repository contains information on checklist production deployment that any team/organisation should consider before push their system into production.

## List 

- [ ] use version control system setup (e.g Git) and push to accessible repository
- [ ] create readme for documentation setup and deployment
- [ ] setup monitoring and alerting system (4 golden signals)
    - [ ] latency [e.g newrelic]
    - [ ] traffic [e.g newrelic]
    - [ ] saturation [e.g grafana]
    - [ ] error [e.g newrelic, sentry, pinger, fabric (for mobile)]
- [ ] setup (centralised) logging system
- [ ] use ENV or dynamic configuration
- [ ] setup database and storage backup mechanism
- [ ] use controllable domain (not IP or 3rd party domain) : especially if being used by external system
- [ ] setup auto deployment (with auto testing as well)
- [ ] setup load balancer
- [ ] setup force update mechanism (mobile)
- [ ] setup auto-logout mechanism (mobile)
- [ ] setup push notification handler (mobile)
- [ ] setup controllable and dynamic config for base_url, etc (mobile)
- [ ] basic analytics (GA especially for web)
- [ ] setup mechanism for changes on deployment (e.g migration db mechanism)
- [ ] make sure the system can handle load for upcoming predicted throughput


