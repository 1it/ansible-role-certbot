# Certbot  
Role to setup and configure Certbot (letsencrypt)

## Requirements  
Ansible version => 2.3.0  

## Role tags:  
  - certbot - setup certbot 
  - cronjob - create or update Cron job file
  - dhparams - create dhparams.pem file  

## Vars  
```yaml
dhparams: true
dhparams_bits: 2048
cronjob: true
cronjob_hour: 2
cronjob_minute: 30
cronjob_weekday: '*'
```

