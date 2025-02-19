# Spring Application Advisor Workshop
## Feb 2025

Lets get ready for Automating Software Migrations with Spring Application Advisor (workshop).

Manually upgrading dependencies and code is slow, error-prone, and costly. In this hands-on workshop, we’ll explore how OpenRewrite and Spring Application Advisor enable automated, continuous migrations for Spring applications.

## Agenda:
- Intro to OpenRewrite – Automating large-scale code and dependency updates
- Live Demo – Showcasing the power of automated migrations
- Writing OpenRewrite Recipes – Customizing transformations for your codebase
- Spring Application Advisor – Connecting your repositories, creating pull requests
- Continuous Migration Strategies 
- Troubleshooting / Q&A

Bring your laptop and a Git repository—by the end, you’ll have migration automation in place, and a strategy to move forward.

The workshop will be led by our Spring Advocate & Champion DaShaun Carter.

## Prerequisites

Access to `Spring Enterprise` repository

```bash
mvn dependency:get -Dartifact=com.vmware.tanzu.spring:application-advisor-cli-macos-arm64:1.1.2 -Dpackaging=tar
mvn dependency:get -Dartifact=com.vmware.tanzu.spring:application-advisor-server:1.1.2 -Dpackaging=jar
```
> `mvnd`, `mvnw` will also work
