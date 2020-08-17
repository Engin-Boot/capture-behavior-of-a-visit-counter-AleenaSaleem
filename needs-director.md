# Visit-counter for a Director

## Scenario: Show patient visits during working days and holidays

### Given: An active sensor that differentiates between patient-card and non-patient-card

### When: There is an entry, sensor identifies the type of card in place

### Then: Based on number of different patient-cards sensed, sensor reports it

## Scenario: Compute parking slots to reserve for visiting specialists

### Given: An active sensor that can sense incoming and outgoing vehicles

### When: a vehicle enters, sensor alloacates a parking slot(if >5 are available)

### Then: Among the five slots left unfilled, reserve one for visiting specialist
