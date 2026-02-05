Automatic Deployment of Web-site on Nginx server on EC2 using Terraform and Ansible.

<img width="1909" height="487" alt="image" src="https://github.com/user-attachments/assets/78cfba4d-f858-4dc4-9dbf-69f3b9c3657a" />

Automated deployment system that takes code from GitHub push to production without manual intervention.
Built a GitHub Actions-based CI/CD pipeline that automatically builds, tests, and deploys applications when code is pushed to the repository.

Key Features:
✓ Fully Automated — Push code → automatic testing → automatic deployment to server
✓ Secure Secrets — GitHub Secrets integration for safe credential management
✓ Multi-Environment — Separate workflows for staging and production deployments
✓ Rollback Capability — Automatic rollback if deployment fails health checks

Results:
Deployment time: 30+ minutes → under 5 minutes
Manual errors: Eliminated through automated testing
Deployment confidence: 100% (tests must pass before deploy)
