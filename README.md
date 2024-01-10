# methodologies

## monitoring
### audience/event tracking
- matomo - https://fr.matomo.org/
- graphana - https://grafana.com/
### bug tracking
- sentry - https://sentry.io/welcome/

## documentation
### diagrams
- mermaid: https://mermaid-js.github.io/mermaid/#/
- plantUml: https://plantuml.com/fr/

## code versionning
### Git
#### Github
#### Gitflow

## Architecture
- https://www.brainboard.co/

## CI/CD
### Github/Actions
### CircleCI
### AWS/CodePipeline
### environment management
- docker
- kubernetes
- nx -> https://nx.dev/

## Python
### project templates
- project template instanciator - https://github.com/cookiecutter/cookiecutter
### environment
- deps and envs manager - Poetry -> https://github.com/python-poetry/poetry
- deps / no env needed - PDM -> https://github.com/pdm-project/pdm/
### tests
- tests - PyTest
- snapshot - Snapshottests
- multi env - tox
- freeze time -> https://github.com/spulec/freezegun
### framework
#### Django
##### DRF
##### profiling
- https://kracekumar.com/post/profiling_django/

## JS
### typing
#### TypeScript
##### training
- https://github.com/type-challenges/type-challenges
### tests
#### Jest
#### Storybook
### architecture
#### Atomic Design

## database
### SQL
#### training
- https://sqlzoo.net/
#### Postgres
### MongoDB
### DBaaAPI
- https://postgrest.org/

## network
### HTTP
- https://www.baeldung.com/cs/http-versions

## data emgineering
### solutions
- https://posthog.com/

## Design Patterns
### MVC
### clean architecture
### hexagonal design
- https://dev.to/abh1navv/hexagonal-architecture-3ocl
### Domain Driven Design
https://en.wikipedia.org/wiki/Domain-driven_design
### Test Driven Development

## tests
### performance
- test/compare performances
- http benchmarking -> https://github.com/mcollina/autocannon
  - usage : `npx autocannon http://localhost:8888/pdfs`
### coverage
#### Codecov
### emailing
- maildev - local emailing server -> https://github.com/maildev/maildev
### tunneling
- ngroc -> redirect url to localhost
- https://webhook.site/ -> generate a webhook url for tests

## terminal
- zsh
  - oh-my-zsh
  - fzf-tab
  - zhc-autosuggetions
- fig -> https://fig.io/

## IDE
### vscode
#### settings
#### extensions
##### HTTP client
- thunder client -> https://marketplace.visualstudio.com/items?itemName=rangav.vscode-thunder-client
- REST client -> https://marketplace.visualstudio.com/items?itemName=humao.rest-client

## Recipes
### create a FastAPI project
1. create a github repo and clone it locally -> `git clone {url}`
2. in the project folder initialize a poetry project -> `poetry init`
3. use virtualenvs with poetry for local debugging -> `poetry config virtualenvs.create true --local`
4. install fast and uvicorn -> `poetry add fastapi uvicorn`
5. create dockerfile and docker-compose files
6. install pre-commit hook -> `poetry add pre-commit -D`
### project templates
- fullstack FastAPI -> https://github.com/tiangolo/full-stack-fastapi-postgresql
- fastAPI nano -> https://github.com/rednafi/fastapi-nano
