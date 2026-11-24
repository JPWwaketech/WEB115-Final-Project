# WEB115-Final-Project-Space Colony Problems 
# Contributors: 
Tanvir Virdi: Documentation and Story Theme
James Watson: Story Flowchart and Story Theme
# Application Overview: 
A colony on Mars is losing power. We must decide on how to get resources to gain back power for the planet  
# Story Flowchart: Space Colony Crisis:
```
flowchart TD
A[Wake Up on Mars Colony] --> B[Emergency Alert: Colony Losing Power]
B --> C{First Priority?}
C -->|Repair Reactor| D[Go to Reactor Room]
C -->|Check Life Support| E[Go to Life Support Center]
C -->|Investigate Distress Signal| F[Travel to Communication Tower]
D --> G{Solve Reactor Puzzle?}
G -->|Success| H[Restore Partial Power]
G -->|Fail| Z1[Ending: Reactor Meltdown] 
E --> I{Allocate Remaining Oxygen?}
I -->|Protect Civilians| J[Colony Population Survives]
I -->|Protect Scientists| K[Research Team Survives] 
F --> L{Answer Distress Signal?}
L -->|Yes| M[Discover Alien Technology]
L -->|No| N[Ignore Signal and Return]
H --> O[Access Colony Mainframe]
J --> O
K --> O
M --> O
N --> O 
O --> P{Final Decision} 
P -->|Use Alien Tech| Q[Ending: Alien-Powered Future]
P -->|Evacuate Colony| R[Ending: Mars Evacuation]
P -->|Repair Systems Manually| S[Ending: Colony Saved]
P -->|Take Control Yourself| T[Ending: Dictator of Mars]
```
