[TrazPort-Craze]
A 3D isometric railway and logistics simulation game inspired by OpenTTD, built with TypeScript, React, and Three.js with an interactive underground cutaway view.

Focused on large-scale regional train logistics, multi-layered infrastructure engineering, and evolving economic supply chains—targeted for web browsers and a Windows 11 desktop release.

Core Design Pillars (v1.0 Scope)
Multi-Level Rail Infrastructure & 3D Cutaway

Build surface tracks, elevated crossing bridges (vertically deferred), tunnels, and multi-level underground railway stations.
Terrain elevation constraints affect grades, route planning, and train physics.
3D-layer-aware block/path signaling, traffic congestion tracking, and bounded deadlock recovery.
Regional Networks Over City Micro-Management

Engineered around vast regional rail corridors linking cities, raw resources, and industrial plants.
Larger station passenger catchment areas than OpenTTD to favor major regional hubs.
In-city transit is intentionally streamlined to Metro, Tram, and S-Bahn feeder networks.
Period-Accurate Historical Progression

Transition through Steam → Diesel → Electric eras across distinct economic regions.
No modular train-part customization—instead, rich, historically inspired locomotives, EMUs/DMUs, and rolling stock driven by technological milestones and regional economics.
Dynamic Cargo Demand & Financial Analytics

City and industrial cargo needs evolve dynamically based on population growth, industrial output, and resource availability.
Strict separation of Operating vs. Capital expenditures, monthly deficit alerts, and a 12-month financial & cargo analytics dashboard.
Creation, Portability & Modding

Intuitive urban planning Map Editor.
Data-driven JSON modding architecture for vehicles, eras, regions, cargo, and industries.
Portable, cross-platform .json save files.
Tech Stack
Simulation Engine: Pure TypeScript deterministic tick & graph architecture (SimState)
3D Rendering: Three.js isometric camera with multi-layer underground cutaway
UI / HUD: React + TypeScript (TopHud, compact inspectors, AnalyticsModal)
Target Platforms: Modern Desktop Browsers & Windows 11 (via Electron / Tauri packaging)
Roadmap Note
v1.0: Complete core economic, multi-level rail, historical era, analytics, map editor, and modding systems.
Post-v1.0: Sandbox Mode (unlimited funds) and expanded scenario tools.
