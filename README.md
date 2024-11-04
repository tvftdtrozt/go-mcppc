# ⚙️ **Shipwright CLI**

> streamline your GitHub release workflow

---

### Install

```bash
npm i -g shipwright
```

### Commands

```bash
shipwright init       # setup repo
shipwright bump       # bump version
shipwright changelog  # generate changelog
shipwright publish    # create GitHub release
```

### Example Workflow

```bash
shipwright bump minor
git push
shipwright publish
```

### Integrations

* GitHub Actions
* GitLab CI
* Slack Webhooks

MIT © [shipwright.dev](https://shipwright.dev)
