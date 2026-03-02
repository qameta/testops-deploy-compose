# CHANGELOG

## 2026-03-01

- Starting from 26.1.1 max value accepted `TESTOPS_TASKEXECUTOR_COREPOOLSIZE` is 50.
- decreased default value for S3_MAXCONCURRENCY down to 100.


## 2025-08-28

- Updates env files with registry and repo names
- adds this CHANGELOG.md
- adds hardcoded 5 minutes sync interval ALLURE_SCHEDULER_INTEGRATION_EXPORT to all configs
- adds ALLURE_LOGIN_OPENID_REFRESHTOKEN for OpenID configuration to define the side controlling user sessions
  - **testops-openid** folder
  - env file example, parameter: USE_OPENID_REFRESH_TOKEN
- explicitly using SPRING_PROFILES_ACTIVE: compose,rabbitmq to set rabbitmq by default for the application.