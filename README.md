Table of Contents

- [Initial project](#initial-project)
- [Practice 1](#practice-1)
  - [Requires](#requires)
- [Practice 2 (Implement CircleCI/GitHub workflow for make CI CD)](#practice-2-implement-circlecigithub-workflow-for-make-ci-cd)
  - [Deploy manual on Heroku](#deploy-manual-on-heroku)
  - [Make CI from your github](#make-ci-from-your-github)
  - [Make CD continue CI](#make-cd-continue-ci)

## Initial project

Follow below

https://loopback.io/getting-started.html

https://loopback.io/doc/en/lb4/todo-tutorial.html

> Use yarn or npm up to you

---

## Practice 1

1. Create application for management student in class for collect test score
2. Can collect test per term
3. `/exports` return json with condition (not require generate from Rest-CRUD)
   1. Can filter by studentId, Term/Year

### Requires

- ERD with `https://plantuml.com/sequence-diagram`
- Internal APIB `https://apiblueprint.org`
- Docker
- Docker-Compose
- Test
- Database PostgreSQL
- Make CRUD with `https://loopback.io/doc/en/lb4/Rest-Crud-generator.html`

## Practice 2 (Implement CircleCI/GitHub workflow for make CI CD)

### Deploy manual on Heroku

[heroku](https://www.heroku.com)

### Make CI from your github

- test
- build
- publish

### Make CD continue CI

- receive publish
- deploy - such as [heroku](https://www.heroku.com)
