# Family Cash Card - CI/CD Pipeline

![Build](https://github.com/DarkoGNU/family-cash-card/actions/workflows/gradle.yml/badge.svg)
![SAST](https://github.com/DarkoGNU/family-cash-card/actions/workflows/codeql.yml/badge.svg)
![DAST](https://github.com/DarkoGNU/family-cash-card/actions/workflows/stackhawk.yml/badge.svg)
![Deployment](https://github.com/DarkoGNU/family-cash-card/actions/workflows/deployment.yml/badge.svg)

CI/CD Pipeline using GitHub Actions for the Family Cash Card API

See working app on:
- API: [https://pipeline.darkognu.eu/cashcards](https://pipeline.darkognu.eu/cashcards)
    - example login: sarah1
    - example password: abc123
- API specification: [https://pipeline.darkognu.eu/swagger-ui.html](https://pipeline.darkognu.eu/swagger-ui.html)

Features:
- Java CI with Gradle (includes unit testing)
- CodeQL SAST security analysis
- SCA security analysis: Dependency Review, Dependabot
    - Dependency Review - on pull request
    - Dependabot - regular scanning (https://github.com/DarkoGNU/family-cash-card/security/dependabot)
- StackHawk DAST Security Analysis
- Automatic deployment to VPS server
