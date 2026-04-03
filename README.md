# OSDCloud Deployment Repository

Dit repository bevat alle configuratie, scripts en assets die nodig zijn voor het uitvoeren van **OSDCloud** deployments binnen onze organisatie.

OSDCloud wordt gebruikt voor het **snel, consistent en geautomatiseerd installeren van Windows** (inclusief drivers en basisconfiguratie), vaak in combinatie met **Microsoft Intune en Windows Autopilot**.

---

## 📦 Wat is OSDCloud?

OSDCloud is een PowerShell‑gebaseerde oplossing van **David Segura (OSDeploy)** waarmee Windows rechtstreeks vanuit de cloud kan worden geïnstalleerd, zonder traditionele MDT/SCCM infrastructuur.

Belangrijke kenmerken:
- Cloud‑based OS deployment
- Ondersteuning voor moderne hardware
- Ideaal voor Autopilot / Modern Workplace scenario’s
- Lichtgewicht en snel op te zetten

Meer informatie:  
👉 https://osdcloud.osdeploy.com

---

## 📁 Repository structuur

```text
.
├── Config/
│   ├── OSDCloud.json
│   └── OSDCloudGUI.json
│
├── Drivers/
│   └── <Vendor>\<Model>\
│
├── Scripts/
│   ├── PreOS/
│   ├── PostOS/
│   └── Custom/
│
├── Branding/
│   ├── Wallpapers/
│   └── Logos/
│
├── Docs/
│   └── Runbooks/
│
└── README.md
