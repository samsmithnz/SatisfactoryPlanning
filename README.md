# Satisfactory v1 Planning

First pillar: create a surplus of 10 of everything for a mall. This creates a steady backlog of items for construction 

## Space elevator total parts needed
The space elevator parts is the ultimate goal - these parts aren't used for anything else, and knowing what we need helps us plan for each step.

| Project Part | ![#f03c15](https://placehold.co/15x15/f03c15/f03c15.png) Phase 1 | ![#c5f015](https://placehold.co/15x15/c5f015/c5f015.png) Phase 2 | ![#1589F0](https://placehold.co/15x15/1589F0/1589F0.png) Phase 3 | ![#FFA500](https://placehold.co/15x15/FFA500/FFA500.png) Phase 4 | Total |
| ------------ | ------- | ------- | ------- | ------- | ----- |
| Smart Plating | ![#f03c15](https://placehold.co/15x15/f03c15/f03c15.png) **50** | ![#c5f015](https://placehold.co/15x15/c5f015/c5f015.png) **500** | 1,000 | 5,000 | 6,550 |
| Automated Wiring | 0 | ![#c5f015](https://placehold.co/15x15/c5f015/c5f015.png) **100** | 750 | 60,000 | 60,850 | 
| Versatile Framework | 0 | ![#c5f015](https://placehold.co/15x15/c5f015/c5f015.png) **500** | ![#1589F0](https://placehold.co/15x15/1589F0/1589F0.png) **2,500** | 10,000 | 13,000 | 
| Adaptive Control Unit | 0 | 0 | ![#1589F0](https://placehold.co/15x15/1589F0/1589F0.png) **100** | 8,000 | 8,100 | 
| Modular Engine | 0 | 0 | ![#1589F0](https://placehold.co/15x15/1589F0/1589F0.png) **500** | 2,500 | 3,000 | 
| Assembly Director System | 0 | 0 | 0 | ![#FFA500](https://placehold.co/15x15/FFA500/FFA500.png) **4,000** | 4,000 | 
| Magnetic Field Generator | 0 | 0 | 0 | ![#FFA500](https://placehold.co/15x15/FFA500/FFA500.png) **4,000** | 4,000 | 
| Nuclear Pasta | 0 | 0 | 0 | ![#FFA500](https://placehold.co/15x15/FFA500/FFA500.png) **1,000** | 1,000 | 
| Thermal Propulsion Rocket | 0 | 0 | 0 | ![#FFA500](https://placehold.co/15x15/FFA500/FFA500.png) **1,000** | 1,000 | 

(from https://satisfactory.fandom.com/wiki/Space_Elevator)

Production requirement calculations
| Phase	| Item	| Total required for phase |	target per minute |	Dependencies |
| ----- | ----- | ----- | ----- | ----- | 
| ![#FFA500](https://placehold.co/15x15/FFA500/FFA500.png) 4	| Assembly Directory System	| 4000	| 4	| Automated Wiring 60p/min + Adaptive Control Unit 8p/min |
| ![#FFA500](https://placehold.co/15x15/FFA500/FFA500.png) 4	| Magnetic Field Generator	| 4000	| 4	| Versatile Framework 10p/min |
| ![#FFA500](https://placehold.co/15x15/FFA500/FFA500.png) 4	| Nuclear Pasta	| 1000	| 1	| none |
| ![#FFA500](https://placehold.co/15x15/FFA500/FFA500.png) 4	| Thermal Propulsion Rocket	| 1000	| 1	| Modula Engine 2.5 p/min |
| ![#1589F0](https://placehold.co/15x15/1589F0/1589F0.png) 3	| Versatile Framework	| 2500	| 10	| none | 
| ![#1589F0](https://placehold.co/15x15/1589F0/1589F0.png) 3	| Adaptive Control Unit	| 100	| 2	| automated wiring 15p/min (note that we need to upscale or store enough for 8 p/min) |
| ![#1589F0](https://placehold.co/15x15/1589F0/1589F0.png) 3	| Modular Engine	| 500	| 2	| smart plating 4p/min (note that we need to upscale or store enough for 2.5 p/min) |
| ![#c5f015](https://placehold.co/15x15/c5f015/c5f015.png) 2	| Smart Plating	| 500	| 4	| none |
| ![#c5f015](https://placehold.co/15x15/c5f015/c5f015.png) 2	| Automated Wiring	| 100	| 15 | none	| 
| ![#c5f015](https://placehold.co/15x15/c5f015/c5f015.png) 2	| Versatile Framework	| 500	| 10 | none | 
| ![#f03c15](https://placehold.co/15x15/f03c15/f03c15.png) 1	| Smart Plating	| 50	| 2	| none (note that we need to upscale or store enough for 4 p/min) |

