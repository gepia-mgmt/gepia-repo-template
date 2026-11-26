# GEPIA project repository

**GEPIA — Grupo Estudiantil de Proyectos de Ingeniería Aplicada.**

This repository was created from the GEPIA project template. It uses GitHub Issues and Pull Requests as the live source of truth:

- **Requirement** = issue
- **Acceptance criterion** = sub-issue of the requirement
- **Task** = pull request
- **Evidence** = commits, test output, screenshots and links inside the PR

Markdown files describe the project; they do not replace issue/PR status.

Spanish version: [README.es.md](README.es.md)

## 1. Create your repository

1. Open the template: <https://github.com/gepia-mgmt/gepia-repo-template>
2. Click **Use this template → Create a new repository**.
3. Choose **your personal GitHub account** as owner. **Do not transfer ownership to the organization.**
4. Use a clear name, related to your project topic.
5. Choose public or private according to the PM’s instructions.

## 2. Grant access

- If the repository is **private**, add the PM/instructor as a collaborator with **Read** access.
- If the repository is public, the PM can add it to the Project without extra access.

## 3. Verify labels

The template includes `.github/workflows/setup-labels.yml`.

1. Open **Actions → GEPIA — setup labels**.
2. It should run on the first push. If it did not, click **Run workflow**.
3. Confirm that labels such as `type:requirement`, `type:acceptance`, `type:task`, `priority:must` and `area:software` exist under
   **Issues → Labels**.

## 4. Verify issue forms

Open **Issues → New issue**. You should see:

- **Requirement**
- **Acceptance criterion**

Blank issues should be disabled.

## 5. Create the first work items

The first issue will be the project description definition. Make sure to do this initial task before the next step.

1. Open one **Requirement** issue.
2. Create one **Acceptance criterion** issue that says "Inclusion to GEPIA org" and add it as a **sub-issue** of the requirement.
3. Open a **Pull Request** as the first task.
   - Link the requirement and the acceptance criterion.
   - Use `Closes #<AC issue>` only if the PR completes that criterion.
   - Make sure that you adjusted the README.md file for this first requirement.
   - Put commits, test logs and evidence in the PR.

## 6. Report the repository to the PM

This is the final setup step. Once you had your first requirement in Closed state, report to your PM so it can be added to the GEPIA Project.

Open an issue here:

<https://github.com/gepia-mgmt/gepia-management/issues/new>

Title:

```text
[REPO] owner/repository-name
```

Include:

- repository URL;
- your GitHub username;
- team members;
- public/private visibility;
- whether the PM has read access (required for private repositories);
- confirmation that the label workflow ran;
- confirmation that the issue forms work;
- links to the first requirement, acceptance criterion and PR.

Do not assume the repository is tracked automatically just because it exists.

## 7. Working language

Use **English** for project development artifacts. This is encouraged for:

- repository name and description;
- issue titles and descriptions;
- PR titles and descriptions;
- code, identifiers and commit messages;
- README and technical documentation;
- diagrams, test names and evidence captions.

You can use Spanish in the project, but keeping the technical record in English makes the project easier to review, reuse, publish and share with international collaborators.

## 8. Project documentation

Use Markdown for:

- objectives and justification;
- architecture and design decisions;
- user documentation;
- reports.

Keep live status in issues, PRs and the GitHub Project. Do not duplicate status in Markdown.
