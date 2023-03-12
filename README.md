# Satisfactory v1 Planning

- First pillar: create a surplus of 10 of everything for a mall. This creates a steady backlog of items for construction 

- Second pillar: Plan a dedicated space elevator production area:

## Space elevator total parts needed
The production of space elevator parts is the ultimate goal - these parts aren't used for anything else, and knowing what we need helps us plan for each step.

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

## Production requirement calculations
| Phase	| Item	| Total required for phase |	target per minute |	Dependencies |
| ----- | ----- | ----- | ----- | ----- | 
| ![#FFA500](https://placehold.co/15x15/FFA500/FFA500.png) 4	| Assembly Directory System	| 4000	| 4	| Automated Wiring 60p/min + Adaptive Control Unit 8p/min |
| ![#FFA500](https://placehold.co/15x15/FFA500/FFA500.png) 4	| Magnetic Field Generator	| 4000	| 4	| Versatile Framework 10p/min |
| ![#FFA500](https://placehold.co/15x15/FFA500/FFA500.png) 4	| Nuclear Pasta	| 1000	| 1	| none |
| ![#FFA500](https://placehold.co/15x15/FFA500/FFA500.png) 4	| Thermal Propulsion Rocket	| 1000	| 1	| Modula Engine 2.5 p/min |
| ![#1589F0](https://placehold.co/15x15/1589F0/1589F0.png) 3	| Versatile Framework	| 2500	| 10	| none | 
| ![#1589F0](https://placehold.co/15x15/1589F0/1589F0.png) 3	| Adaptive Control Unit	| 100	| 2	| automated wiring 15p/min (note that we need to upscale or store enough for 8 p/min) |
| ![#1589F0](https://placehold.co/15x15/1589F0/1589F0.png) 3	| Modular Engine	| 500	| 2	| smart plating 4p/min (note that we need to upscale or store enough for 2.5 p/min) |
| ![#c5f015](https://placehold.co/15x15/c5f015/c5f015.png) 2	| Smart Plating	| 500	| 2	| none |
| ![#c5f015](https://placehold.co/15x15/c5f015/c5f015.png) 2	| Automated Wiring	| 100	| 15 | none	| 
| ![#c5f015](https://placehold.co/15x15/c5f015/c5f015.png) 2	| Versatile Framework	| 500	| 10 | none | 
| ![#f03c15](https://placehold.co/15x15/f03c15/f03c15.png) 1	| Smart Plating	| 50	| 2	| none (note that we need to upscale or store enough for 4 p/min) |

If we assume that the first phase of the space elevator will be available around 10 hours in, second phase 25 hours, third phase 50 hours, and last phase 100 hours, we can roughly project how many space elevator parts we will produce (using the rates above), and any short falls. By storing excess production, we can prep for the next phase, simplifying production lines.

| Item | Phase 1 (15 hours) | Phase 1 carryover | Phase 2 (25 hours) | Phase 2 carryover| Phase 3 (50 hours)| Phase 3 carryover | Phase 4 (20 hours) | Phase 4 carryover | 
| ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- |  ----- | 
| Assembly Directory System | | | | | | | 4800 | 800 | 
| Magnetic Field Generator | | | | | | | 4800 | 800 | 
| Nuclear Pasta | | | | | | | 1200 | 200 | 
| Thermal Propulsion Rocket | | | | | | | 1200 | 200 | 			
| Adaptive Control Unit ||  | | | 6000 | 5500 | 7900 | -100 |
| Modular Engine | | ||  | 6000 | 5500 | 7900 | 5400 |							
| Automated Wiring | | | 22500 |	22000 |	44500 |	43750 |	61750 |	1750 | 
| Versatile Framework |	 |	 |	16750 |	16250 |	46250 |	43750 |	55750 |	45750 | 
| Smart Plating | 1800 | 1750 | 4750 | 4250 | 10250 | 9250 | 11650 | 6650 |

