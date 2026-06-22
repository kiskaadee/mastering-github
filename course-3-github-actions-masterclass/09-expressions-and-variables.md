# GitHub Actions CI/CD: Expressions & Variables

## 1. Course Information
* **Course:** GitHub Actions Masterclass: From Beginner to Advanced
* **Module:** 09 - Expressions & Variables
* **Status:** ⬜ To Do | 🟨 In Progress | 🟩 Completed
* **Date Studied:** YYYY-MM-DD
* **Estimated Time:** [X] hours

---

## 2. Overview & Workflow Triggers
*High-level summary of the module, outlining which triggers (on: push, pull_request, workflow_dispatch, etc.) and runner scopes are explored.*

---

## 3. Cornell Notes & Cue Column

| Key Automation Cues | Detailed Explanations & Workflow Configurations |
| :--- | :--- |
| **Contexts vs Variables?** | Explain differences in evaluation time (expression syntax)... |
| **Concurrency Limits?** | How to control running jobs on simultaneous pushes... |

---

## 4. YAML Snippets & Syntax Reference

```yaml
# Syntax Example
name: Workflow Demo
on: [push]
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout code
        uses: actions/checkout@v4
```

### Automation Demo/Exercise Checklist:
- [ ] Initialize repository workflow `.github/workflows/`
- [ ] Implement conditional execution (e.g. `if: github.ref == 'refs/heads/main'`)
- [ ] Verify execution outputs in the GitHub Actions tab.

---

## 5. Review Questions
1. [Question 1]
2. [Question 2]

---

## 6. Summary & CI/CD Best Practices
*Quick summary of how these workflow concepts reduce build time, clean up artifacts, or optimize runner usage.*
