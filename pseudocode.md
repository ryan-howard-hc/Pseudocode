# REPOTTING A HOUSEPLANT

## OVERVIEW AND GOAL

Eventually, any houseplant will grow. Just like people purchasing larger garments to fit their growing needs, a plant will require a larger container to maintain growth or just remain healthy in general. When it is ready, it can show a few signs that are indicative of this stage.
<br>

### MATERIALS/VARIABLES
    1. A vessel about 10-25% larger than the previous vessel
<br>
        - Properties for container: let vessel = {
            potWidth
            potDepth
        };
        obtainVessel
<br>
    2. Appropriate soil for the species being repotted. Err on the side of caution if you do not know the proper soil, and obtain well-draining mix. (Root rot is our number one enemy for the majority of houseplants!!!)
<br>
        -VARIABLES for the soil medium: let soil = { 
            acquireSoil
            waterLoving
            waterSensitive
        };
        soilPorosity, soilAmount
<br>
    3. A chopstick or butter knife to loosen around the edges if the plant is wedged in there, as well as a space to repot
<br>
        -VARIABLES required for execution of function: wedgeItem, plantStuck, removePlant, findSpace, clearSpace
<br>
    4. (Optional) If the species in question is a climber, purchase a moss pole or a piece of wood with twine or a rough rope. Also make sure your pot has enough depth to keep the support stable.
<br> 
        -VARIABLE for optional climbing species: mossPole
<br>
    5. FOR EXECUTION
<br>
        -VARIABLES: loosenSoil, packSoil, waterSoil


### Operations
    1. REMOVE plant from current vessel
    2. REPOTTING plant into new vessel

## FUNCTIONS:
- REMOVE
    1. FUNCTION findSpace
        IF area < 5x5ft 
        THEN clearSpace() = "Clear yo room jabroni"
    2. FUNCTION acquireSoil
        IF plant === waterSensitive
        THEN soilPorosity() = "Add perlite or orchid bark or get porous soil"
        ELSE waterLoving() = "Any potting mix"
    3. FUNCTION removePlant
        IF plant === plantStuck
        THEN wedgeItem() = "Loosen plant from current vessel"
- REPOTTING
    4. FUNCTION obtainVessel
        IF vessel != 10-25%% larger
        THEN 
            RUN obtainVessel() = "Get a larger pot"
        ELSE
            IGNORE
    5. FUNCTION loosenSoil 
        - Loosen soil and roots at base of plant following removal from previous pot.
    6. FUNCTION packSoil
        - Add some soil at the bottom
        - Place plant in center and try to level plant approximately half an inch below top of the pot
        - 