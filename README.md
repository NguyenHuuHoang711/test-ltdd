# Monorepo

Go backend + Flutter mobile + Flutter web

---

# Project Structure

backend/ → Go API
app/ → Flutter mobile
web/ → Flutter web
infra/ → terraform / k8s
docs/ → documentation

---

# Development Workflow

1 create feature branch

```
git checkout -b feature/feature-name
```

2 push

```
git push origin feature/feature-name
```

3 create PR

4 CI runs

5 review

6 merge

---

# Branches

main → production
develop → staging

feature/* → development

---

# Commit Convention

feat: new feature
fix: bug fix
refactor: code change
docs: documentation
test: test
chore: maintenance

example:

```
feat(auth): login api
fix(user): nil pointer
```

---

# Pull Request Rule

* no push to main
* PR required
* CI must pass
* review required
