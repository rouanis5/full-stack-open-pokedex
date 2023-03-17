# Exercice 1

## Q1

> Some common steps in a CI setup include linting, testing, and building. What are the specific tools for taking care of these steps in the ecosystem of the language you picked?

Python:

- Linting: Flake8, PyLint
- Testing: unittest, pytest, nose2
- Building: setuptools, distutils, wheel

JavaScript:

- Linting: ESLint, JSHint
- Testing: Jest, Mocha, Jasmine
- Building: Webpack, Gulp, Grunt

## Q2

> What alternatives are there to set up the CI besides Jenkins and GitHub Actions?

- Travis CI - a popular open-source CI tool that can be used with many programming languages and platforms.
- CircleCI - another popular cloud-based CI tool that supports a wide range of programming languages and platforms.
- GitLab CI/CD - GitLab provides an integrated CI/CD pipeline that can be used with GitLab repositories, and it supports many programming languages and platforms.
- Bitbucket Pipelines - an integrated CI/CD pipeline that can be used with Bitbucket repositories and supports many programming languages and platforms.
- TeamCity - a commercial CI tool from JetBrains that supports many programming languages and platforms.
- Bamboo - another commercial CI tool from Atlassian that supports many programming languages and platforms.
- Drone - an open-source CI/CD platform that is built on Docker and can be used with many programming languages and platforms.
- Codeship - a cloud-based CI/CD platform that supports many programming languages and platforms.

## Q3

> Would this setup be better in a self-hosted or a cloud-based environment? Why? What information would you need to make that decision?

The decision to use a self-hosted or cloud-based CI environment depends on several factors, such as the size and complexity of the project, the available resources, and the specific needs of the development team. Here are some factors that can help you decide:

- Budget - self-hosting CI may require more upfront costs for hardware and infrastructure, while cloud-based CI usually has a pay-per-use pricing model.
- Scalability - cloud-based CI can easily scale up or down depending on the needs of the project, while self-hosted CI may require additional resources to handle increased traffic.
- Control - self-hosted CI provides more control over the environment and can be customized to meet specific project requirements, while cloud-based CI may have limitations on customization.
- Security - self-hosted CI can provide better security control as the development team has complete control over the environment, while cloud-based CI may require additional security measures to ensure data protection.
- Maintenance - self-hosted CI requires more maintenance and updates, while cloud-based CI is managed by the provider.

To make a decision, you would need information such as the size and complexity of the project, the available resources, and the specific needs of the development team. Additionally, you would need to consider the costs and benefits of each option, including factors such as scalability, control, security, and maintenance.
