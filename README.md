# GillPad

Source for [gillpad.dev](https://gillpad.dev), the public engineering portfolio of Paden Gillispie.

GillPad presents practical work across infrastructure engineering, cybersecurity, virtualization, automation, Zero Trust access, cloud-native platforms, technical instruction, and mentoring.

## Live Site

- Portfolio: [gillpad.dev](https://gillpad.dev)
- Mentoring and advisory: [gillpad.dev/services.html](https://gillpad.dev/services.html)
- GitHub profile: [github.com/pgill-dev](https://github.com/pgill-dev)
- LinkedIn: [linkedin.com/in/paden-gillispie](https://www.linkedin.com/in/paden-gillispie)

## Purpose

The site is designed to answer four questions:

1. What kinds of systems has Paden built or operated?
2. How does he reason about infrastructure and security?
3. Can he communicate technical decisions clearly?
4. How can someone engage him for mentoring or focused advisory work?

## Featured Work

- Zero Trust engineering lab
- ESXi-to-Proxmox migration and recovery
- Proxmox management tooling
- Kubernetes and service-mesh engineering
- GOAD security range
- Vulnerability and compliance engineering
- Daedalus AI-assisted engineering platform
- GitHub-to-Cloudflare Pages deployment pipeline

## Technology

- Static HTML and CSS
- Git and GitHub
- Cloudflare Pages
- Cloudflare DNS and TLS
- Mermaid diagrams on selected architecture pages

## Repository Structure

```text
.
├── assets/
├── projects/
├── index.html
├── services.html
├── style.css
└── README.md
```

## Local Preview

```powershell
python -m http.server 8080
```

Then open `http://localhost:8080`.

## Deployment

Changes pushed to the configured production branch trigger a Cloudflare Pages deployment.

Recommended workflow:

```powershell
git switch -c feature/mentor-consulting-front-door
git add index.html services.html README.md
git commit -m "Add mentoring and advisory front door"
git push -u origin HEAD
```

Open a pull request, inspect the preview deployment, and merge after validating links, layout, and mobile behavior.

## Security and Privacy

Published material should not contain credentials, tokens, cookies, private keys, unnecessary internal addresses, employer-confidential documentation, other people's PII, or unredacted administrative screenshots.

Organizational examples are sanitized and described at an outcome or architecture level.

## Author

**Paden Gillispie**  
Infrastructure Engineer · Security Practitioner · Technical Mentor · Army Veteran

- [GillPad](https://gillpad.dev)
- [GitHub](https://github.com/pgill-dev)
- [LinkedIn](https://www.linkedin.com/in/paden-gillispie)
