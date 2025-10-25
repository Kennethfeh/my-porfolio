# Kenneth Feh - DevOps Portfolio

A single-page portfolio that documents my transition into DevOps and platform engineering. The site focuses on honest storytelling, highlighting hands-on labs, project write-ups, and the operations background that fuels my move into cloud automation.

## What You’ll Find
- **Intro & About** - why I’m pivoting from recreation centre coordination and teaching into DevOps.
- **Skills Snapshot** - the toolchain I’m actively learning and where I’ve applied it.
- **Project Experience Timeline** - self-directed work alongside prior operations roles.
- **Hands-on Projects** - detailed case studies with GitHub links for EC2 foundations, ECS Fargate, EKS + Helm, and observability stacks.
- **Learning Highlights & Contact** - reflections on what each build taught me plus ways to collaborate.

## Featured Projects
- [AWS EC2 Foundations Lab](https://github.com/Kennethfeh/devops-journey/tree/main/project-1-foundation) - Terraform-based VPC, IAM guardrails, and EC2 automation with architecture notes and teardown scripts.
- [ECS Fargate Service Platform](https://github.com/Kennethfeh/devops-journey/tree/main/project-2-containers) - container build pipeline, ECS/Fargate deployment, load balancing, and secrets handling.
- [EKS & Helm Platform Playbook](https://github.com/Kennethfeh/devops-journey/tree/main/project-3-kurbernetes) - cluster provisioning, Helm add-ons, GitOps onboarding, and RBAC practices.
- [CloudWatch Observability Starter](https://github.com/Kennethfeh/devops-journey/tree/main/projecct-4-monitoring) - metrics, logs, alarms, and runbooks for tracing ECS workloads.
- [Observability Control Plane](https://github.com/Kennethfeh/devops-journey/tree/main/project-5-monitoring-advanced) - Prometheus, Loki, Tempo, Grafana, and OpenTelemetry collectors running on Kubernetes.

## Skills In Context
- **Cloud & Containers** - AWS core services, ECS/Fargate, Amazon EKS, and containerization with Docker.
- **Infrastructure as Code** - Terraform modules, environment bootstrapping, and GitOps experiments with Argo CD and Flux.
- **CI/CD & Automation** - GitHub Actions workflows that build, test, and deploy lab environments.
- **Observability & SRE** - CloudWatch dashboards, Prometheus/Grafana stacks, incident playbooks, and continuous learning around SLIs/SLOs.
- **Collaboration Mindset** - communication, documentation, and coordination skills gained from recreation centre operations and teaching roles.

## Local Development
Serve the static site with any web server. One option:

```bash
# From the project directory
cd my-porfolio
python3 -m http.server 8000
# Visit http://localhost:8000 in your browser
```

## Deployment
The site is static. Deploy it with Vercel, GitHub Pages, Netlify, or any static hosting provider. For Vercel CLI:

```bash
vercel
vercel --prod
```

## Housekeeping
- The repository is currently named `my-porfolio` (typo). Renaming it to `my-portfolio` keeps things polished.
- Update the project links above if you restructure folders or publish new labs.

## Contact
- Email: [kennethfeh@gmail.com](mailto:kennethfeh@gmail.com)
- GitHub: [github.com/Kennethfeh](https://github.com/Kennethfeh)
- Location: Seoul, Korea
