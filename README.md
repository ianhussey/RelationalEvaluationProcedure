# Relational Evaluation Procedure

Training and testing of comparative relations via One-To-Many Relational Evaluation Procedure

## Open Source License - GPLv3+

Copyright (c) Ian Hussey 2016 (ian.hussey@ugent.be)

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

## Procedure

### Phases

#### Training 1:

A1 > B1, A2 < B2

#### Training 2:

A1 < C1, A2 > C2

#### Training 3:

A1 > B1, A2 < B2, A1 < C1, A2 > C2

#### Testing:

B1 (>) C1, B2 (<) C2

### Corrective feedback

Training: "CORRECT" at 750ms, "WRONG" at 1500ms.

Testing: None.

### Counterbalancing

location of left and right stimuli are counterbalanced so that participants must respond to the relation between the stimuli rather than the stimuli themselves. Location of response options is not counterbalanced, as this isn't strictly necessary.



