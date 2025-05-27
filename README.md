# 🌐 AITM Coding Club — Open-Source Projects

Student-built, community-maintained software that solves real problems while teaching members modern collaboration workflows.

[MIT License](LICENSE)

## Repository layout

```text
open-source-projects/
├── attendance-tracker/      # Django + React QR attendance app
├── ev-charging-system/      # Node.js backend for EV billing
├── flutter-chat-app/        # Realtime chat (Flutter + Firebase)
├── ideas/                   # Brainstorming & proposal templates
│   └── project-proposals.md
├── .github/                 # Workflows, issue/PR templates
└── README.md                # ← you are here
```

## Live projects


| Project            | Tech stack          | One-line overview                           |
| ------------------ | ------------------- | ------------------------------------------- |
| Attendance Tracker | Django · React     | Scan QR codes, store & export attendance    |
| EV Charging System | Node.js · MySQL    | Meter apartment EV usage, automate billing  |
| Chat App           | Flutter · Firebase | Mobile chat with realtime messages & pushes |

> **Want to help?** Look for issues labelled **`good first issue`** or **`help wanted`**.

## Quick-start contribution guide

1. **Fork** the repo, then clone your copy
   `git clone https://github.com/<your-user>/open-source-projects.git`
2. Create a feature branch
   `git checkout -b feat/<short-description>`
3. Add code / docs (or create a new project folder)
   `git add . && git commit -m "feat: <concise summary>"`
4. **Push** and open a **pull request**
   `git push origin feat/<short-description>`

`main` is protected — at least **one review** and **green CI** are required before merging.

## Project guidelines

- **One folder per project**; keep codebases isolated.
- Each project **must include a `README.md`** with:
  - Overview, tech stack, key features
  - Local setup / run instructions
  - Screenshots or demo GIFs (if available)
- Follow language-specific style guides; write meaningful commits.
- Choose an appropriate **license** for your project (MIT, GPL, etc.).
- Be kind and abide by our [Code of Conduct](CODE_OF_CONDUCT.md).

## Propose a new idea

Add a section to **`ideas/project-proposals.md`** using this template, then open a PR:

```text
Project Name:
Description:
Problem it solves:
Tech stack:
Potential mentors / team members (optional):
```

Maintainers will review, label, and help bootstrap a new folder.

## Community & contact

- **Discussions tab** — Q&A, pairing requests, brainstorming.
- **Email** — [code@anjuman.edu.in](mailto:code@anjuman.edu.in)

## License

Unless a sub-project states otherwise, all content in this repository is released under the **MIT License**.
See [`LICENSE`](LICENSE) for the full terms.
