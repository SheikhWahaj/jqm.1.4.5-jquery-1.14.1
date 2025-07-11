jQuery Mobile 1.4.5 + jQuery UI 1.14.1 Compatibility Patch

## 📦 Overview

This repository provides modified and patched versions of:

- **jQuery Mobile 1.4.5**
- **jQuery UI 1.14.1**

The goal is to make these two libraries fully compatible with each other, overcoming the default limitation where **jQuery Mobile 1.4.5 only officially supports jQuery UI up to version 1.13**.

---

## 🔧 Why This Exists

By default:
- **jQuery Mobile 1.4.5** is a stable release.
- However, it is not compatible with **jQuery UI 1.14.1** due to breaking changes and lack of updates in JQM.
- Many projects still rely on JQM but need newer UI components or fixes introduced in jQuery UI 1.14.x.

This repository includes the necessary modifications to allow both libraries to coexist and function properly together.

---

## ✅ Features

- Modified `jQuery Mobile 1.4.5` to handle changes in `jQuery UI 1.14.1`.
- Ensures compatibility without breaking core mobile UI components.
- Tested with core widgets like **collapsibles**, **dialogs**, **tabs**, and **sortable**.
- Fixes common integration issues (e.g., event conflicts, method overrides).

---
