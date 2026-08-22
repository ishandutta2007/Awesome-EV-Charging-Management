# Awesome-EV-Charging-Management

## Top EV Charging Management Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on EV Charging Station Management, Charge Point Operations, Roaming, Billing & Energy Management*  

**Last updated: August 2026**



This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **EV Charging Management**. These tools manage charging stations, drivers, charging sessions, payments, tariffs, smart charging, energy management, roaming, charger monitoring, fleet charging, and EV charging networks.



**Examples** include ChargeLab, AMPECO, Driivz, EV Connect, Monta, ChargePoint, Virta, GreenFlux, Shell Recharge Solutions, and ChargeHub, alongside broader EV charging infrastructure and e-mobility platforms.



**Open-source emphasis**: This section is heavily expanded with open-source Charging Station Management Systems (CSMS), OCPP implementations, EV charger software stacks, OCPI platforms, energy-management frameworks, charging simulators, and supporting projects that can be combined to build self-hosted EV charging infrastructure.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites or project repositories.



## Table of Contents



- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [Additional Strong Open-Source Options](#additional-strong-open-source-options)

- [Frameworks for Building Custom EV Charging Platforms](#frameworks-for-building-custom-ev-charging-platforms)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Platform / Product | Description | Starting Pricing | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- |
| **[ChargeLab](https://chargelab.co/)** | Cloud platform providing charging station management, network operations, remote monitoring, payments, and OCPP integrations. | Level 2 AC: $25/port/month; DCFC Level 3: $50/port/month (10% off for 3-yr, 20% off for 5-yr commitment). Fleet plans start at $25/port/month. | Free forever plan for residential EV drivers via ChargeLab Rewards ($0 monthly fee, earns $0.10/kWh rewards); Commercial platform provides a free live guided product demo upon request. |
| **[AMPECO](https://www.ampeco.com/)** | White-label EV charging management platform for operating public, workplace, fleet, and residential charging networks. | Starts at ~$10–$15/charger/month (tiered CPO platform pricing based on connector volume, plus one-time onboarding setup). | No self-service free tier; provides a free 1-on-1 live platform demo and custom proof-of-concept consultation upon request. |
| **[Driivz](https://driivz.com/)** | Enterprise EV charging software platform supporting charging network management, billing, energy management, roaming, and smart charging. | Starts at ~$50–$67/port/month ($600–$800/port/year entry enterprise tier for network management). | No free forever plan; offers a free live interactive product demo and custom sandbox pilot upon request for utilities and large CPOs. |
| **[EV Connect](https://www.evconnect.com/)** | EV charging network management platform providing station operations, driver services, payments, monitoring, and energy management. | Starts at $120–$240/port/year (approx. $10–$20/port/month; bundled Software+ subscriptions available; also available via CaaS monthly plans). | 1-year free software subscription included with select certified hardware purchases (e.g., Schneider Charge Pro); free live demo on request. |
| **[Monta](https://monta.com/)** | Integrated EV charging platform covering charge point management, payments, roaming, charging operations, and energy workflows. | Private/Home: €0/month; Commercial Pro plan starts at ~$4.95–$6.00/charge point/month (plus 10% transaction fee on pay-per-charge billing). | Free forever plan for up to 3 charge points across multiple locations via the Monta Charge app (includes basic smart charging and private access control). |
| **[ChargePoint](https://www.chargepoint.com/)** | Large-scale EV charging ecosystem providing charging network management, hardware, driver services, fleet charging, and energy management. | Starts at $240–$300/port/year (approx. $20–$25/port/month prepaid on 1–5 year terms); Essential Cloud Plan for CPF50 starts at $0 upfront software fee (funded via driver session fees). | Free forever driver mobile app & basic residential home charging management; free 30-day cloud trial/demo sandbox for commercial site hosts on request. |
| **[Virta](https://www.virta.global/)** | EV charging platform supporting charging-network operations, payments, roaming, smart charging, energy management, and white-label services. | Starts at ~€10–€20/charging point/month (entry CPO management package depending on connector volume and add-on modules). | Free forever driver app for public charging access and roaming; commercial CPO platform provides a free live product demo and guided technical walkthrough on request. |
| **[GreenFlux](https://www.greenflux.com/)** | EV charging management platform providing charge point operations, smart charging, roaming, billing, and energy optimization. | Starts at ~$5–$20/charge point/month (entry smart charging & roaming management tier for CPOs and eMSPs). | Free driver roaming app access; CPO platform offers a free product demo and technical trial evaluation on request. |
| **[Shell Recharge Solutions](https://www.shell.com/mobility/electric-vehicle-charging.html)** | EV charging management and infrastructure platform supporting public, workplace, fleet, and home charging ecosystems. | Starts at ~€4–€8/socket/month for commercial/business cloud management (or €0 monthly for home app users with standard roaming transaction fees). | Free forever home charging app (Shell Recharge App for personal charging points); free commercial fleet & site pilot consultation on request. |
| **[ChargeHub](https://chargehub.com/)** | EV charging platform and driver network providing charging-station discovery, network connectivity, payments, and roaming management. | $4.29/month (ChargeHub Plus driver subscription waiving activation fees across 160k+ ports); B2B Passport Roaming starts at ~$50/month base integration fee. | Free forever basic tier (ChargeHub Map & community app with access to search and basic payment routing across 120,000+ North American locations). |
| **[EVBox Everon](https://www.evbox.com/)** | EV charging management software and services for operating charging stations and networks (transitioning to partner management platforms). | Previously starting at ~€4.50–€6.00/connector/month (users transitioning to partner platforms like Tap Electric / Blink). | 30-day free trial on partner migration platforms (e.g., Tap Electric / Clenergy EV); basic home app was free for a single residential charger. |
| **[Blink Charging](https://blinkcharging.com/)** | EV charging hardware and network-management platform supporting station operations, payments, monitoring, and charging services. | Starts at $18–$25/port/month (Host-Owned Blink Network subscription) or $0/month upfront on Blink-Owned hybrid revenue-share model. | Free forever driver account & mobile app; $0-cost host option via Blink-as-a-Service / revenue share plan; free host portal demo on request. |
| **[Wallbox (myWallbox)](https://www.wallbox.com/)** | EV charging ecosystem providing connected chargers, charging management, energy management, and fleet solutions. | Basic tier: €0/month; Standard/Business management tier starts at ~€4.50–€6.50/charger/month (or 5% transaction fee on pay-per-charge). | Free forever Basic plan for unlimited private chargers (includes group management, scheduling, automated locking, and energy stats); 30-day free trial for Business tier. |
| **[FLO](https://www.flo.com/)** | EV charging network and software platform supporting charging station management, monitoring, driver services, and fleet charging. | Starts at ~$24/port/month (commercial network management fee plus ~10% transaction processing fee). | Free forever FLO mobile app for personal charging stations & public roaming; free site host consultation and demo on request. |
| **[SWTCH Energy](https://swtchenergy.com/)** | EV charging management platform focused on multi-unit residential, workplace, fleet, and commercial charging. | Starts at ~$15–$20/port/month (or bundled Charging-as-a-Service starting around $50/month including hardware, installation, and software). | Free driver app for tenant/workplace billing; commercial hosts get a free initial site survey & software platform demo on request. |
| **[Electrify America](https://www.electrifyamerica.com/)** | Large-scale EV charging network with software supporting charger operations, driver access, payments, and network management. | $7.00/month (Electrify America Pass+ subscription giving ~25% discount per kWh); Commercial fleet/site host custom agreements. | Free forever Pass tier (standard pay-as-you-go charging access, station discovery, and charger status monitoring with no monthly subscription fee). |
| **[Noodoe EV (Noodoe EV OS)](https://www.noodoe.com/)** | EV charging management platform for commercial charging networks, including station monitoring, billing, access management, and operations. | Starts at ~$15–$25/port/month for Noodoe EV OS cloud management (autonomous revenue generation, automated recovery, and load management). | Free driver web app (scan and pay without registration); 30-day sandbox pilot and free live demo for commercial operators. |
| **[ev.energy](https://www.evenergy.io/)** | EV charging software and energy-management solutions supporting connected charging infrastructure and utility demand-response. | Free core smart charging app; ev.energy SOLAR premium tier starts at £5/month or £50/year (commercial utility platform via custom contracts). | Free forever core plan for smart home EV charging & utility reward programs; 30-day free trial for ev.energy SOLAR features. |
| **[AmpUp](https://www.ampup.io/)** | EV charging network software supporting charging management, fleet operations, payments, and charger monitoring. | Starts at ~$15–$20/port/month (or $180–$240/port/year for entry Commercial/Fleet Management software). | Free driver mobile app; 30-day free software trial / demo sandbox for site hosts and fleet managers. |
| **[Fimer](https://www.fimer.com/)** | Connected EV charging infrastructure and management capabilities for commercial and energy applications (OCPP-compliant hardware with CPMS integration). | Hardware-agnostic OCPP hardware; bundled companion software or partner CPMS starting at ~€5–€10/charger/month (e.g., via eCarUp / Fortum). | Free local configuration tools & basic companion app; free CPMS tier available via partner integrations (e.g., eCarUp free tier with transaction fees). |
| **[Kempower ChargEye](https://kempower.com/)** | Cloud-based charging management and monitoring platform for Kempower DC charging infrastructure and fleet depots. | Starts at ~€30–€50/charging station/month (cloud monitoring and dynamic power distribution platform for Kempower fast chargers). | Free basic local commissioning interface; free ChargEye cloud live demo and guided technical onboarding on request. |
| **[Alpitronic Hypercharger](https://www.alpitronic.it/)** | High-power EV charging infrastructure supported by software and operational tooling for charger management and monitoring. | Open OCPP hardware stack; companion diagnostic monitoring or partner CSMS starting at ~€8–€15/charger/month (or freemium via eCarUp with 10% session fee). | Free local service and diagnostics software (Alpitronic Service Tool); free partner cloud tier available via eCarUp for basic management. |
| **[Siemens eMobility (Sifinity)](https://www.siemens.com/)** | EV charging infrastructure and digital-management ecosystem (Sifinity Fleet / DepotFinity) for commercial, fleet, workplace, and public charging. | Sifinity Fleet / DepotFinity Basic tier starting at ~€15–€30/connector/month (scales up for dynamic load management and day-ahead market optimization). | Free basic driver mobile app; free live demo and 30-day proof-of-concept pilot for fleet/enterprise customers on request. |
| **[ABB E-mobility (ChargerSync / ABB Ability)](https://www.abb.com/)** | EV charging infrastructure and digital software ecosystem supporting charger management, monitoring, fleet charging, and energy integration. | ChargerSync is €0/month for Terra AC hardware; enterprise ABB Ability Management Console starts at ~€12–€25/port/month for commercial networks. | Free forever ChargerSync app & web portal for Terra AC wallboxes (manage up to 50 home/workplace chargers, scheduling, RFID, and energy statistics). |



## Open-Source GitHub Projects



- **[CitrineOS](https://github.com/citrineos/citrineos)**  

  Open-source Charging Station Management System (CSMS) designed around OCPP 2.0.1. It provides modular charging-station management, smart charging, reservations, authorization, device management, and extensibility. :contentReference[oaicite:0]{index=0}



- **[CitrineOS Core](https://github.com/citrineos/citrineos-core)**  

  The core CitrineOS runtime containing OCPP routing, charging-station management logic, APIs, operator UI, persistence, messaging, and infrastructure components. It supports OCPP 1.6 and 2.0.1. :contentReference[oaicite:1]{index=1}



- **[EVerest](https://github.com/EVerest/EVerest)**  

  Linux Foundation Energy-backed open-source modular EV charging stack. It supports AC/DC charging, OCPP, ISO 15118, IEC 61851, DIN SPEC 70121, hardware drivers, energy management, OTA updates, and custom charger development. :contentReference[oaicite:2]{index=2}



- **[EVerest libocpp](https://github.com/EVerest/libocpp)**  

  Open-source OCPP implementation used within EVerest, supporting OCPP 1.6J, 2.0.1, and newer protocol capabilities. :contentReference[oaicite:3]{index=3}



- **[SteVe](https://github.com/steve-community/steve)**  

  Open-source web application for managing EV charging stations through OCPP. It is particularly useful for experimentation, development, testing, and smaller CSMS deployments.



- **[Open e-Mobility](https://github.com/open-e-mobility)**  

  Open-source ecosystem for EV charging management, with components that can be combined with OCPP chargers and charging infrastructure.



- **[Open Charge Point Protocol implementations](https://github.com/search?q=OCPP&type=repositories)**  

  Community-developed OCPP libraries and implementations for connecting EVSE hardware with charging-station management systems.



- **[OpenOCPP](https://github.com/EVerest/libocpp)**  

  Open-source embedded OCPP software for EV charging stations, designed to provide reusable OCPP functionality in charger firmware. The project supports OCPP 1.6J and 2.0.1. :contentReference[oaicite:4]{index=4}



- **[EVerest Simulators](https://github.com/EVerest/EVerest)**  

  EV charging simulation capabilities for testing charger behavior, OCPP communication, CSMS integrations, and end-to-end charging workflows.



- **[OCPI implementations](https://github.com/search?q=OCPI+EV+charging&type=repositories)**  

  Open-source implementations of the Open Charge Point Interface protocol for roaming, charge-point discovery, tariffs, sessions, and interoperability between charging networks.



- **[OCPP-Java](https://github.com/ChargeTimeEU/Java-OCA-OCPP)**  

  Java implementation of OCPP useful for building and testing charging-station management systems and EV charging integrations.



- **[OCPP Python](https://github.com/mobilityhouse/ocpp)**  

  Python implementation of OCPP that can be used to build EV chargers, CSMS applications, simulators, and charging integrations.



- **[Open Charge Meter](https://github.com/OpenEVSE/open_evse)**  

  Open EV charging hardware/software ecosystem useful for building and experimenting with connected EV charging infrastructure.



- **[OpenEVSE](https://github.com/OpenEVSE/open_evse)**  

  Open-source EVSE controller project supporting configurable EV charging hardware and control logic.



- **[OpenEnergyMonitor](https://github.com/openenergymonitor)**  

  Open-source energy monitoring ecosystem useful for integrating electricity measurements, energy consumption, solar generation, and EV charging analytics.



- **[OpenEMS](https://github.com/OpenEMS/openems)**  

  Open-source Energy Management System for optimizing distributed energy resources, storage, solar, loads, and EV charging.



- **[Home Assistant](https://github.com/home-assistant/core)**  

  Open-source home automation platform with extensive EV charging and energy integrations, useful for residential smart-charging applications.



- **[evcc](https://github.com/evcc-io/evcc)**  

  Open-source EV charging and energy-management system focused on intelligent charging, solar integration, dynamic electricity prices, and home energy optimization.



- **[SteVe Web UI](https://github.com/steve-community/steve)**  

  Browser-based interface for managing charging stations, transactions, connectors, and OCPP-connected infrastructure.



- **[OCPP Simulator Projects](https://github.com/search?q=OCPP+simulator+EV&type=repositories)**  

  Community simulators for testing charge points, CSMS implementations, OCPP messages, charging sessions, and protocol interoperability.



### Additional Strong Open-Source Options



- **Open OCPP Libraries** for implementing OCPP 1.6, OCPP 2.0.1, and newer protocol versions.

- **Open CSMS Platforms** for managing chargers, transactions, users, authorization, tariffs, and charging sessions.

- **Open OCPI Implementations** for roaming and interoperability between charging networks.

- **Open ISO 15118 Implementations** for Plug & Charge, vehicle-to-grid, and advanced EV-EVSE communication.

- **Open EVSE Firmware** for building customizable charging hardware.

- **Open Charging Simulators** for testing charging stations and CSMS platforms without physical hardware.

- **Open Smart-Charging Algorithms** for load balancing, dynamic tariffs, demand response, and charging optimization.

- **Open Energy Management Systems** for coordinating EV charging with solar, batteries, grids, and building loads.

- **Open EV Fleet Charging Tools** for depot scheduling, charging optimization, and vehicle energy management.

- **Open Charging Analytics** for session analysis, charger utilization, uptime, energy consumption, and revenue analytics.

- **Open Roaming Infrastructure** for connecting independent charging networks.

- **Open Payment Integrations** for implementing charging-session payments and billing workflows.

- **Open Tariff Engines** for calculating charging costs based on energy, time, power, location, and dynamic pricing.

- **Open Hardware Abstraction Layers** for connecting EVSE controllers, meters, RFID readers, power electronics, and communication modules.

- **Open Vehicle-to-Grid (V2G) Projects** for bidirectional charging and grid-interactive EV infrastructure.



**Frameworks for building custom EV charging platforms**: Combine **CitrineOS** or **SteVe** for CSMS functionality, **EVerest/libocpp** for charger-side software and OCPP, **OCPI** implementations for roaming, **OpenEMS/evcc** for energy management, **PostgreSQL + Redis** for operational data and low-latency state, **Kafka/RabbitMQ/MQTT** for event processing, and **Grafana** for charging-network monitoring.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Prioritize genuinely open-source projects with an accessible repository or clearly documented open license.

5. Include the supported protocol where relevant, such as OCPP, OCPI, ISO 15118, or IEC 61851.

6. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- EV charging platforms differ substantially in scope: some are complete CSMS/network-management products, while others focus on charger firmware, OCPP, roaming, energy management, or hardware integration.

- Some projects listed under the open-source ecosystem are **building blocks rather than complete commercial-platform replacements**.

- SaaS capabilities, product names, ownership, pricing, supported protocols, and licensing models can change over time.

- Always verify the current license before using an open-source project commercially.

- Production EV charging infrastructure should be evaluated for security, protocol compliance, payment security, uptime, hardware compatibility, grid requirements, and applicable regulatory requirements.



---



**Made for EV charging operators, CPOs, eMSPs, fleet operators, energy companies, charger manufacturers, developers, and e-mobility engineers.**  

Let's make EV charging infrastructure more open, interoperable, intelligent, and accessible.
