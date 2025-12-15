# Enterprise Catalog for Power Apps

A centralized catalog and item deployer for Power Apps environments — designed to make multi-environment rollouts predictable, repeatable, and easy for both makers and administrators.

This repository contains the **unpacked source solution** for the Enterprise Catalog, ready to import and extend.

---

## 📋 Prerequisites

Before importing this solution, ensure the following prerequisites are met:

✔ Power Apps access with appropriate permissions  
✔ A Dataverse environment (default or custom)  

✔ **Power Platform Catalog is installed and enabled**  
   📘 [Power Platform Catalog](https://learn.microsoft.com/en-us/power-apps/maker/data-platform/catalog-overview)

✔ Required connectors are available and can be assigned  

> **Note:**  
> This solution is provided as *unmanaged* to allow customization and source control.


## 🚀 Overview

The **Enterprise Catalog** is a solution for organizing, deploying, and managing reusable Power Apps artifacts, components, and templates across multiple environments. It provides a centralized approach for:

- Standardizing components and templates
- Managing multi-environment rollouts
- Enabling discovery and reuse of artifacts
- Supporting development best practices across teams

📌 Built for: Power Apps (Canvas & Model-Driven), Dataverse, and Power Platform environments.

---

## 📌 Features

- Central catalog of reusable items
- Deployment workflows for consistent multi-env updates
- Support for environment variables and connection references
- Structured solution packaging for version control

---

## 📋 Prerequisites

Before importing this solution you need:

✔ Power Apps access with appropriate permissions  
✔ Dataverse environment (default or custom)  
✔ If applicable: required connectors configured

> **Note:** This solution is provided as *unmanaged* to allow customization and source control.

---

## 📥 Importing the Solution

1. Download the latest release ZIP (*EnterpriseCatalog.zip*) from the [Releases](https://github.com/<DEIN_USER>/<DEIN_REPO>/releases) page.
2. Open **Power Apps** → **Solutions**.
3. Click **Import** and select the downloaded ZIP.
4. Assign your **Connection References** when prompted.
5. Complete the import and publish customizations.

---

## ⚙ Configuration

### Connection References

Power Platform will prompt you to connect required services. Make sure all connectors are valid before finishing the import.

---

## 🧩 Using the Catalog

Once installed:

1. Access the Catalog app from the Power Apps home.
2. Browse available catalog items.
3. Select items to deploy to your target environment.
4. Track deployments and rollbacks as needed.

---

## 📈 Versioning & Maintenance

This repo uses **Semantic Versioning**:

| Tag | Meaning |
|-----|---------|
| `v1.0.0` | Initial Delivery |
| `v1.x.x` | Feature / incremental changes |
| `v2.0.0` | Major redesign or breaking changes |

Releases are available on the GitHub **Releases** page with ZIP downloads.

---

## 🧠 Development Workflow

Recommended internal process:

1. Make changes in the unpacked solution folder.
2. Test in a sandbox environment.
3. Pack and export with `pac solution pack`.
4. Tag a new version and publish a Release.

---

## 🤝 Contributing

Contributions are welcome! Please follow standard GitHub practices:

1. Fork the repository
2. Create a feature branch
3. Submit a Pull Request with clear description

---

## 📄 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

## 💡 Inspiration

This solution is based on principles for standardized deployment and reuse across environments, as discussed in this article:

👉 *Centralized Catalog + Item Deployer for Multi-Environment Rollouts*  
https://www.linkedin.com/pulse/centralized-catalog-item-deployer-multi-environment-rollouts-brandt-2ykpe/

---

## 📩 Support

For questions, ideas, or help:
- Create an issue in this repo
- Contact the author via LinkedIn

---

