# TECHNOLOGY RADAR

## Techniques


### Infrastructure as code 💚
Setting up a new environment or changing an infrastructure should be scripted and executed automatically by a build pipeline.

### Serverless architecture 💚
Serverless applications are easier to manage and scale so this should be the default approach when setting up a new service or a website.

### Functional programming 💚
It's easy to write testable code when no state is mutated

### Object-oriented programming 💛
It's OK to use OOP just keep it SOLID!

### Continuous Delivery (CD) 💚
Deploy automatically to production after all automated tests pass.

### Feature-toggles 💚
Use feature-switches to enable new functionality in production for limited set of users.

### Release from master branch 💚
Keep master branch up-to-date and ready to be deployed to production at any moment in time.

### Feature branching 🔻
Keep branches short-lived and merge to master as soon as possible.

### Rebase merging 💚
Use rebase over merge to keep git history clean.

### Consumer-driven contract testing 🔵
Using PACT or other forms of contract testing to keep RESTful services in sync.

### UI Component Library 💚
Shared UI components help us build consistent UI faster across various digital assets

### Pull requests for code reviews 💚
Useful to pick any issues, learn more, and share the knowledge using the power of GitHub


## Platforms


### AWS 💚
AWS is our cloud platform of choice. Of course we should keep an eye on other platforms so the solutions we build should have business logiс decoupled from the infrastructure whenever possible.

### Auth0 💚
Managed Identity Provider service


## Languages and Frameworks


### NodeJS 💚
It's cool and fast enough plus works really well for serverless architectures, e.g. running in AWS lambdas

### JavaScript as a first class language 💚
Combined with static typing JavaScript allows rich full-stack programming experience

### TypeScript 💚
Superset of JavaScript adds types, intellisense, ES6 syntax and much more

### React.js 💚 :cool:
Our default choice for UI

### Bulma 🔵
CSS framework based on Flexbox and built with Sass.

### CssModules (PostCSS, CssNext) 💚
Incapsulated CSS with variables

### Storybook 💚
Interactive UI component development / testing library

### Styleguidist 🔵
Component development environment with hot reloaded dev server and a living style guide, competitor to Storybook

### Terraform 🔵
Deploying cloud services using Terraform gives an opportunity to use different cloud providers.

### serverless.com framework 💚
Deploying APIs to AWS Lambda is easy with this proven framework, it just works


## Tools


### Buildkite 💚
Managed build service of choice

### GitHub 💚
Everything is there including this document.

---
Legend: 💚 preferred, 💛 accepted, 🔵 assess, 🔻 avoid

