# REPOTTING A HOUSEPLANT

## OVERVIEW AND GOAL

Eventually, any houseplant will grow. Just like people purchasing larger garments to fit their growing needs, a plant will require a larger container to maintain growth or just remain healthy in general. When it is ready, it can show a few signs that are indicative of this stage.
<br>

## VARIABLES
### MATERIALS
    1. A vessel about 10-25% larger than the previous vessel
<br>
        - Properties for container: let vessel = {
            potWidth
            potDepth
        };

    2. Appropriate soil for the species being repotted. Err on the side of caution if you do not know the proper soil, and obtain well-draining mix. (Root rot is our number one enemy for the majority of houseplants!!!)
<br>
        -Variables for the soil medium: soilPorosity, soilAmount

    3. A chopstick or butter knife to loosen around the edges if the plant is wedged in there, as well as a space to repot
<br>
        -Variable required for execution of function: wedgeItem, , findSpace, clearSpace

    4. (Optional) If the species in question is a climber, purchase a moss pole or a piece of wood with twine or a rough rope. Also make sure your pot has enough depth to keep the support stable.
<br> 
        -Variable for optional climbing species: mossPole
<br>

## FUNCTIONS:
- Preparation
    1. FUNCTION clearSpace
        IF area < 5x5ft 
        THEN clear