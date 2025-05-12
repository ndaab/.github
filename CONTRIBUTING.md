# Contributing to ndaab
Thank you for your interest in contributing. 

We welcome contributors from all backgrounds, cultures, and skill levels. Whether you're a developer, designer, translator, linguist, or someone passionate about preserving African heritage, there's a place for you here.

## Table of Contents

## Ways of Contributing
Fill our [contributors form]() in order to start contributing to ndaab.
- **Code** – Help with frontend, backend, or AI/ML components
- **Design** – Improve UI/UX or contribute to branding
- **Language Content** – Translate, record voice samples, or help verify content
- **Ideas & Feedback** – Suggest features, report bugs, or share user insights
- **Docs & Community** – Write documentation, help onboard others, or promote the project

____________________________________________

### Contributing with code
#### Overview
- Fork the relevant repository.
- Clone it to your local machine.
- Follow the setup instructions in `README.md`.
- Create your branch e.g. `feature` : `git checkout -b feature/the-feature-name`
- Push and submit a pull request (PR) with a clear description.
- Engage in review and iteration - we are collaborative.

#### Code Contribution Guidelines
We follow a clear and collaborative workflow for contributing code. Whether you're fixing a bug, adding a feature, or improving documentation, follow these steps to ensure smooth development.

**Note**: Always use the present tense.
- Do not say: Added new feature or Adding new feature for example.
- Say: Add new feature.

**1. Fork and clone the repository:**
```bash
git clone <repo-url>
cd <repo-name>
```
**2. Create a branch:**
 Branch anemes should describe your work clearly. Our naming format is `<type>/<subsystem>-<short-description>` e.g. `feat/quiz-changed-leaderboard-diamond-points` whose purpose is to add a leaderboard feature.

**🚫 Do not do this**:
- `new-feature`
- `my-branch`
- `dev-work`
- `feature`
- `bugfix`

  These are vague and unhelpful to others reading your repo history or reviewing PRs.

| Component | Description | Example |
| --------- | ----------- | ------- |
| `<type>`   | What kind of change you're making | `feat`, `fix` |
| `<subsystem>` | What part of the app/product you're touching | `auth`, `content` |
| `<short-description>` | Brief summary using hyphens instead of spaces | changed-leaderboard-diamond-points |

##### Accepted Branch Types
| Type | Purpose |
| ---- | ------- |
| `ci` | Continuous Integration / GitHub Actions changes |
| `hotfix` | Critical bug fix |
| `docs` | Documentation updates |
| `test` | Adding or improving tests |
| `refactor` | Code cleanup or restructure (no behavior change) |
| `chore` | Non-functional updates e.g. config updates |
| `fix` | Bug fix |
| `feat` | New feature e.g. adding a new module or screen or endpoint |

##### Common Subsystems
| Subsystem | Purpose |
| ---- | ------- |
| `auth` | Login, register, password reset, etc. |
| `content` | Language content uploads or changes. |
| `core` | App-wide settings, navigation, theme, etc. |
| `admin` | Admin dashboard and controls. |
| `infra` | Cloud infra, AWS, deployments. |
| `backend` | APIs, DB schema, backend logic. |
| `ui` | 	Components, screens, layout changes |
| `quiz` | 	Game logic, question flow, gamification |
| `language` | 		Language content, translation, levels |

##### ✍🏾  Examples
| Branch name | Purpose |
| ---- | ------- |
| `fix/auth-login-crash` | Fix crash on login screen |
| `docs/core-readme-update` | Update README |
| `refactor/auth-onboarding` | Refactor the onboarding logic |
| `chore/infra-env-setup` | Add AWS credentials to env file |
| `feat/language-bassa-support` | Create new language support |
| `ci/core-test-step` | Add CI ste[ for testing |

**3. Write clean, documented code:**
- Follow existing coding standards in the project such as:
  - Appropriately documenting functions
  - Appropriately doumenting modules
  - Writing tests for every endpoint etc.
- Keep commits small and focused. Use this [guide](https://www.conventionalcommits.org/en/v1.0.0/) for writing commit messages.
- Add comments where helpful.
- Use environment files for API keys and other credentials. **Never** hardcode secrets.

**4. Test Your Work**: Before pushing your changes:
- Run tests if available
- Ensure your work runs without issues
- Manually test your feature or bug fix
- **Never** push directly to the `main` or `online` branch.

**5. Open a Pull Request**: Depending on the project convention, open a PR to `main` or `dev` or `staging`
##### Format for a PR message

```markdown
## Overview
Briefly describe the feature or fix or contribution you have made.

## Changes made
- What issue did you work on?
- What files did you modify?
- What functionlity did you add/change?

## Screenshots
Optional - add if applicable

## Checklist
- [ ] Code compiles/runs correctly
- [ ] No breaking changes
- [ ] Tested and working

## Additional notes
Optional - add if applicable
```
**6. Code review and changes:**
- Another team member or maintainer will review your PR.
- Be open to feedback and push updates to **the same** branch.
- Once approved, your PR will be merged.

💡 **Pro Tips**
- Ask questiond when unsure!
- Use draft PRs to show your progress.
- Link issues using `Closes #issue-number` in PR description to auto-close them **if permitted.**

#### Creating an issue
1. Write issue description.
2. Specify the project under which it falls
3. Use appropriate labels to describe the issues.

##### Format for writing an issue
```markdown
## User Story
### Overview
Overview of issue you are creating. Use the appropriate role at the start always e.g. `As a user`, `As a developer`, 'As a product owner`

### Description
Detailed description of the issue.

### Screenshots
Optional - add if applicable

### Acceptance criteria

### Additional notes
Optional - add if applicable
```

### Contributing to design

### Contributing to language content

### Contributing with ideas and feedback

### Docs and the community

## Communication
- For issues, open a GitHub issue in the relevant repo
- For broader discussions or team contact: info@ndaab.com
- For community discussions: [WhatsApp](https://chat.whatsapp.com/EkhlxYhIsF3D9EkzLZoaw3) or [Zulip](https://ndaab-comm.zulipchat.com/join/eozn2w5jtppn5mptjezom3b2/)

## Code of Conduct
We believe in respectful, inclusive collaboration. See our [Code of Conduct](./CODE_OF_CONDUCT.md).

Thank you for helping us preserve Africa’s rich cultural heritage.
