# 10SE6A Task 2 - Project Documentation

In this Assessment Task 

## Part A - Data Selection & Game Attributes

### Data Selection (implemented with Examples:)

For each card's statistics I've selected easy-to-understand attributes that each player, even many that aren't familiar with vehicles can interpret or easily get to understand. These specifications include: Build Year, Price, Top Speed, ANCAP Safety Ratings, Engine, and Drive Type. 

Two tables that display attributes both an example and an additional table portraying an example of a real car.

|Attributes     |Example        |
|-------------------|-------------|
|Build Year         |Year (e.g 2000)       |
|Price              |Price (e.g $100,000)      |
|Top Speed          |Kilometres (e.g 120 KM/H)            |
|Safety Rating       |Safety Rating Stars (e.g 5 STARS)  |
|Engine    |(e.g 250 HP)         |
|Drive Type  |(e.g 4WD)|

An example of a 'real' car including authentic attributes would include:

**Example Car:** *2020 Volvo XC60 T6 R-Design Auto*
|Attributes     |Example        |
|-------------------|-------------|
|Build Year         |2020       |
|Price              |$37,000      |
|Top Speed          |180 KM/H            |
|Safety Rating       |5 STARS |
|Engine    |316 HP         |
|Drive Type  |AWD|

### Game Attributes (Ranked from the most powerful to the least powerful)
**Engine (HP):** For my first and most powerful game attribute, I chose Engine Power. Engine Power is strong in Top Trumps as it is an easily comparable unit due to diverse performance in cars with horsepower directly affecting how fast and powerful a car is. However, measuring engine can be unfair as sports cars will almost always surpass regular everyday or family cars in this category.

**Top Speed:** For my second attribute, I chose Top Speed. Top Speed is another performance based attribute which shows how the limit to how fast the car can travel. Top Speed is a strong category for Top Trumps as it is easy to rank amongst cars, however it can also be unfair as like Engine Power, this attribute also favours sporty and high-performing cars.

**Build Year:** For my third attribute, I chose to add the Build Year. The Build Year attribute, unlike Engine and Top Speed, does not support higher performance cars over other vehicles. It is a good choice for Top Trumps as it displays how new a car is, using improvements factors like efficiency, safety, design and technology. It is a fair aspect however it can be unfair towards older model cars that are higher in quality.

**Price:** For my fourth attribute, I chose Price. Price is a more useful attribute in the Top Trumps game as it portrays the car's market value, making it easier to compare the different cars. It also adds a realistic detail to Top Trumps but it can be an unfair feature because more expensive cars can usually win if cost is picked over a performance or safety category.

**ANCAP Safety Rating:** For my fifth attribute, I chose the ANCAP Safety Rating. The ANCAP Safety Rating is another powerful and fair attribute because it reflects how safe and well a car can protect people in actual real world crashes and accidents. It balances the advantage of sports cars in other categories as family and everyday cars can now be put into level competition. It is mostly fair, however most newer model cars would have the highest ratings and win this aspect.

**Drive Type:** For my sixth, final and least powerful attribute I chose Drive Type. The Drive Type attribute (4WD, AWD, RWD, etc.) is the weakest as unlike the other statistics including numbered amounts, the Drive measures in categorical form. Drive Type is a more unfair attribute as while it affects performance and the handling of a car, its hard to rank fairly in the game due to the limited range of types.

## Part B - Class Design

### Class - Car:
**Role of this class:** The 'Car' class stores all the information or attributes of a specific vehicle. It is the main source for data used in the card comparisons and displays the information on each card.

**Attributes:** All the attributes for the 'Car' class would include:
- name: String
- picture: Image
- model: String
- price: Float
- buildYear: Integer
- topSpeed: Integer
- safetyStarRating: Float
- enginePower: Integer
- driveType: String

**Methods:** The methods for the 'Car' class would include:

- getCarAttribute(car_attributeName)
- displayCarDetails()

### Class - Card:
**Role of this class:** The 'Card' class represents a Top Trumps card that is used in the game. It contains a 'Car' object and displays the vehicle's attributes and data to the user so players can compare during playing.

**Attributes:** All the attributes for the 'Card' class would include:
- gameCardID
- car

**Methods:** The methods for the 'Card' class would include:
- displayCard


