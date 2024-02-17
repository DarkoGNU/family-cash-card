# Family Cash Card - CI/CD Pipeline

![Build](https://github.com/DarkoGNU/family-cash-card/actions/workflows/gradle.yml/badge.svg)
![SAST](https://github.com/DarkoGNU/family-cash-card/actions/workflows/codeql.yml/badge.svg)

CI/CD Pipeline using GitHub Actions for the Family Cash Card API

Features:
- Java CI with Gradle (includes unit testing)
- CodeQL SAST security analysis
- SCA security analysis: Dependency Review, Dependabot
    - Dependency Review - on pull request
    - Dependabot - regular scanning (https://github.com/DarkoGNU/family-cash-card/security/dependabot)
