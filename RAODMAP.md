# 🗺️ Checklist Review Toolchain – Roadmap

A unified roadmap for the CLI tool and its integrations across VS Code, Jenkins, and Azure DevOps.

---

## ✅ Phase 1: Core CLI Foundation (`checklist-review-cli`)

| Task | Status |
|------|--------|
| Define checklist markdown format | ✅ Done |
| Implement CLI validation logic | ✅ Done |
| Add YAML config support | ✅ Done |
| Exit codes for CI integration | ✅ Done |
| Publish to GitHub under MIT license | ✅ Done |
| Add unit tests and CI pipeline | ⏳ In Progress |
| Add support for custom checklist templates | ⏳ In Progress |

---

## 🧩 Phase 2: VS Code Extension (`checklist-review-vscode`)

| Task | Status |
|------|--------|
| Render checklist with completion indicators | ✅ Done |
| Integrate CLI validation | ✅ Done |
| Add auto-validation on save | ⏳ In Progress |
| Block commits if checklist is incomplete | ⏳ In Progress |
| Publish to VS Code Marketplace | ⏳ Planned |

---

## 🔧 Phase 3: Jenkins Plugin (`checklist-review-jenkins`)

| Task | Status |
|------|--------|
| Add CLI validation step to Jenkins pipeline | ✅ Done |
| Support freestyle and declarative pipelines | ✅ Done |
| Fail builds on incomplete checklist | ⏳ In Progress |
| Publish plugin to Jenkins update center | ⏳ Planned |

---

## ☁️ Phase 4: Azure DevOps Extension (`checklist-review-azure`)

| Task | Status |
|------|--------|
| Add CLI validation to YAML pipelines | ✅ Done |
| Support classic pipelines | ⏳ In Progress |
| Block PR completion if checklist is incomplete | ⏳ Planned |
| Package and publish to Azure Marketplace | ⏳ Planned |

---

## 📦 Phase 5: Toolchain Integration & Release

| Task | Status |
|------|--------|
| Create central GitHub Project board | ✅ Done |
| Define shared versioning strategy | ⏳ Planned |
| Add documentation and usage examples | ⏳ In Progress |
| Create demo repository with all tools | ⏳ Planned |
| Release v1.0.0 across all components | ⏳ Planned |
