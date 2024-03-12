# CI/CD Security Example
This is a minimal example to highlight Direct Poisioned Pipeline Execution  
[https://owasp.org/www-project-top-10-ci-cd-security-risks/CICD-SEC-04-Poisoned-Pipeline-Execution](https://owasp.org/www-project-top-10-ci-cd-security-risks/CICD-SEC-04-Poisoned-Pipeline-Execution).


## Branch Protections
![Branch Protections](branchprotections.png)

## Secrets
![Secrets](secrets.png)

## Howto
Create a new branch and open a pull request. The pull request title can be used for command injection into the pipeline to e.g. access the secrets.  
![PR Example](prexample.png)

This results into a call to google  
![PR Example Agent](prexample-agent.png)
# Other
Made with ❤ in Dortmund