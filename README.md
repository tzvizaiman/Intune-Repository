# Intune Automation Repository

Enterprise-grade Microsoft Intune & Microsoft Graph automation scripts.

Author: Nick Butcher  
GitHub: https://github.com/nihkb007/Intune-Repository  

---

## About This Repository

This repository contains scalable, production-focused automation scripts designed to solve real-world Microsoft Intune and Microsoft Entra ID challenges.

The goal of this project is to provide:

- Reliable automation solutions
- Performance-optimized Microsoft Graph API usage
- Governance-driven device management tools
- Scalable enterprise-ready scripting examples
- Practical solutions for MSP and enterprise environments

All scripts are written with performance, logging, and responsible production deployment in mind.

---

## Featured Script

### Intune Primary User Auto-Assignment & Shared Device Correction

Automatically manages the **Primary User** field in Microsoft Intune based on Entra ID (Azure AD) sign-in activity.

### Key Features

- Automatically assigns Primary User for single-user devices
- Automatically removes Primary User for shared devices
- Clears stale ownership assignments
- Detects multiple-user logins within a defined timeframe
- Optimized Microsoft Graph batching
- Configurable device processing limits
- Timestamped logging with automatic retention trimming
- Report, Test, and Live execution modes
- Designed for scheduled hourly automation

### Why This Matters

Primary User accuracy impacts:

- Intune reporting
- Compliance targeting
- Conditional Access insights
- Asset ownership tracking
- Autopilot visibility
- License alignment
- Governance integrity

In large or fast-moving environments, ownership drift is inevitable.  
This script continuously realigns ownership based on actual sign-in behavior.

---

## Custom Script Development

Need something specific for your environment?

I offer custom Microsoft Intune and Microsoft Graph automation development, including:

- Tenant-wide reporting solutions
- Automation workflows
- Compliance & governance scripting
- Device lifecycle automation
- Microsoft Graph API integrations
- Performance optimization for large environments
- Scheduled automation solutions
- Azure Automation / Runbook conversions

If you are interested in custom scripting or automation work, open an issue or contact me through GitHub.

Donations are also accepted for custom script requests.

---

## Support This Project

If these scripts help you, consider supporting the project:

- ⭐ Star the repository
- 🍴 Fork and contribute
- 💬 Provide feedback
- ❤️ Donate to support continued development

### Donation Options

Cash App: `$nihkolasb`

Your support helps fund continued automation development and new releases.

---

## Requirements

- PowerShell 7.x
- Azure App Registration
- Microsoft Graph Application Permissions:
  - DeviceManagementManagedDevices.ReadWrite.All
  - AuditLog.Read.All
  - User.Read.All
- Admin consent granted

---

## Security & Design Philosophy

These scripts:

- Use application authentication (Client Credentials flow)
- Avoid delegated permissions
- Minimize API calls using batching strategies
- Support scalable automation
- Include logging and safety controls
- Are built for enterprise-grade environments

Designed for responsible and secure deployment.

---

## Roadmap

Planned additions:

- Additional Intune automation utilities
- Reporting enhancements
- Multi-tenant support tooling
- Governance dashboards
- Performance analytics modules
- Expanded automation libraries

---

## License

This project is licensed under the MIT License.

See the LICENSE file for details.

---

## Author

Nick Butcher  
Intune Automation & Enterprise Endpoint Engineering  

GitHub: https://github.com/nihkb007/Intune-Repository
