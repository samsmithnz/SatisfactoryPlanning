# Satisfactory Planning

Primary goals 
- Create a surplus of everything for a mall. This creates a steady backlog of items for construction 
- Plan a dedicated space elevator production area
- Make all designs aesthetically pleasing - include walls, places to walk, color coded, etc.

## Space elevator total parts needed ([Update for v1.0 in progress, with what we know](https://satisfactory.wiki.gg/wiki/Future_content#1.0))
The production of space elevator parts is the ultimate goal - these parts aren't used for anything else, and knowing what we need helps us plan for each step.

| Project Part | ![#f03c15](https://placehold.co/15x15/f03c15/f03c15.png) Phase 1 | ![#c5f015](https://placehold.co/15x15/c5f015/c5f015.png) Phase 2 | ![#1589F0](https://placehold.co/15x15/1589F0/1589F0.png) Phase 3 | ![#FFA500](https://placehold.co/15x15/FFA500/FFA500.png) Phase 4 | ![#A020F0](https://placehold.co/15x15/A020F0/A020F0.png) Phase 5 | Total |
| ------------ | ------- | ------- | ------- | ------- | ------- | ----- |
| Smart Plating | ![#f03c15](https://placehold.co/15x15/f03c15/f03c15.png) **50** | ![#c5f015](https://placehold.co/15x15/c5f015/c5f015.png) **1,000** | 1,000 | 1,250 | 1000 | 4,300 |
| Automated Wiring |  | ![#c5f015](https://placehold.co/15x15/c5f015/c5f015.png) **100** | 750 | 5,000 | 2,500 | 8,350 | 
| Versatile Framework |  | ![#c5f015](https://placehold.co/15x15/c5f015/c5f015.png) **1,000** | ![#1589F0](https://placehold.co/15x15/1589F0/1589F0.png) **2,500** | 1,250 | 640 | 5,390 | 
| Adaptive Control Unit |  |  | ![#1589F0](https://placehold.co/15x15/1589F0/1589F0.png) **100** | 1,000 | 500 | 1,600 | 
| Modular Engine |  |  | ![#1589F0](https://placehold.co/15x15/1589F0/1589F0.png) **500** | 625 | 500 | 1,625 | 
| Assembly Director System |  |  |  | ![#FFA500](https://placehold.co/15x15/FFA500/FFA500.png) **500** | 250 | 750 | 
| Magnetic Field Generator |  |  |  | ![#FFA500](https://placehold.co/15x15/FFA500/FFA500.png) **500**  | 256| 756 | 
| Thermal Propulsion Rocket |  |  |  | ![#FFA500](https://placehold.co/15x15/FFA500/FFA500.png) **250** | 200 | 450 | 
| Nuclear Pasta |  |  |  | ![#FFA500](https://placehold.co/15x15/FFA500/FFA500.png) **100** | ![#A020F0](https://placehold.co/15x15/A020F0/A020F0.png) **1,100** | 1,200 | 
| Biochemical Sculptor |  |  |  |  | ![#A020F0](https://placehold.co/15x15/A020F0/A020F0.png) **1,000** | 1,000 |
| Ballistic Warp Drive |  |  |  |  | ![#A020F0](https://placehold.co/15x15/A020F0/A020F0.png) **200** | 200 |
| AI Expansion Server |  |  |  |  | ![#A020F0](https://placehold.co/15x15/A020F0/A020F0.png) **256** | 256 |

(from https://satisfactory.fandom.com/wiki/Space_Elevator)

## Production requirement calculations
| Phase	| Item	| Total required for phase |	target per minute |	Dependencies |
| ----- | ----- | ----- | ----- | ----- | 
| ![#A020F0](https://placehold.co/15x15/A020F0/A020F0.png) ?	| ?	| ?	| ?	| ? |
| ![#A020F0](https://placehold.co/15x15/FFA500/FFA500.png) 5	| AI Expansion Server	| 256	| 1	| none |
| ![#A020F0](https://placehold.co/15x15/FFA500/FFA500.png) 5	| Ballistic Warp Drive	| 200	| 1	| none |
| ![#A020F0](https://placehold.co/15x15/FFA500/FFA500.png) 5	| Biochemical Sculptor	| 1000	| 1	| none |
| ![#A020F0](https://placehold.co/15x15/FFA500/FFA500.png) 5	| Nuclear Pasta	| 1000	| 1	| none |
| ![#FFA500](https://placehold.co/15x15/FFA500/FFA500.png) 4	| Assembly Directory System	| 500	| 4	| Automated Wiring 60p/min + Adaptive Control Unit 8p/min |
| ![#FFA500](https://placehold.co/15x15/FFA500/FFA500.png) 4	| Magnetic Field Generator	| 500	| 4	| Versatile Framework 10p/min |
| ![#FFA500](https://placehold.co/15x15/FFA500/FFA500.png) 4	| Thermal Propulsion Rocket	| 250	| 1	| Modula Engine 2.5 p/min |
| ![#FFA500](https://placehold.co/15x15/FFA500/FFA500.png) 4	| Nuclear Pasta	| 100	| 1	| none |
| ![#1589F0](https://placehold.co/15x15/1589F0/1589F0.png) 3	| Versatile Framework	| 2500	| 10	| none | 
| ![#1589F0](https://placehold.co/15x15/1589F0/1589F0.png) 3	| Adaptive Control Unit	| 100	| 2	| automated wiring 15p/min (note that we need to upscale or store enough for 8 p/min) |
| ![#1589F0](https://placehold.co/15x15/1589F0/1589F0.png) 3	| Modular Engine	| 500	| 2	| smart plating 4p/min (note that we need to upscale or store enough for 2.5 p/min) |
| ![#c5f015](https://placehold.co/15x15/c5f015/c5f015.png) 2	| Smart Plating	| 500	| 2	| none |
| ![#c5f015](https://placehold.co/15x15/c5f015/c5f015.png) 2	| Automated Wiring	| 100	| 15 | none	| 
| ![#c5f015](https://placehold.co/15x15/c5f015/c5f015.png) 2	| Versatile Framework	| 500	| 10 | none | 
| ![#f03c15](https://placehold.co/15x15/f03c15/f03c15.png) 1	| Smart Plating	| 50	| 2	| none (note that we need to upscale or store enough for 4 p/min) |

If we assume that the first phase of the space elevator will be available around 10 hours in, second phase 25 hours, third phase 50 hours, and last phase 100 hours, we can roughly project how many space elevator parts we will produce (using the rates above), and any short falls. By storing excess production, we can prep for the next phase, simplifying production lines.

| Item | Phase 1 (15 hours) | Phase 1 carry over | Phase 2 (25 hours) | Phase 2 carry over | Phase 3 (50 hours)| Phase 3 carry over | Phase 4 (20 hours) | Phase 4 carry over | 
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

[All items plan](https://satisfactory-calculator.com/en/planners/production/index/json/%7B%22Desc_SpaceElevatorPart_7_C%22%3A%224%22%2C%22Desc_SpaceElevatorPart_6_C%22%3A%224%22%2C%22Desc_SpaceElevatorPart_8_C%22%3A%221%22%2C%22Desc_SpaceElevatorPart_9_C%22%3A%221%22%7D)
