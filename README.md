# test-renovate-config
I would like to
- Make Renovate only consider folder-to-include
- Make it suggest minor and patch updates for folder-to-include/elastic and only consider dockerfiles
- Make it suggest only patch updates for folder-to-include/mariadb and only consider dockerfiles 
- Also, since I'm self hosting renovate on Kubernetes cronjobs on GKE, I'd like to make it execute postUpdateTasks for the whole folder folder-to-include and its subfolders.
