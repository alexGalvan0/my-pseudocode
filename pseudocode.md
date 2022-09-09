# HOW TO MAKE A CUP OF COFFEE

### <u>INIT OBJECTS:</u>
> - **CREATE** CoffeeMaker
> - **CREATE** Person
> - **CREATE** K-Cups
> - **CREATE** K-CupContainer
> - **CREATE** Mug
> - **CREATE** MugCabinete
> - **CREATE** Sink

### <u>PROPERTIES OF OBJECTS:</u>
> - **CoffeeMaker**
>   - Has K-Cup insert
>   - Has water reservoir
>   - Has Temp Sensor
>   - Has coffee dispenser
>   - Has water heater
>   - Has screen for controlls

> - **Person**:
>   - Has 2 hands
>   - Has eyes

> - **K-Cups**:
>   - small circular
>   - Fits into K-Cup insert inside *Coffee Maker*

> - **Mug**:
>   - Goes under coffee dispenser
>   - Holds up to 1.5 cups of coffee
>   - Has handle to pickup and place down by *Person* hands

> - **K-CupContainer**:
>   - can hold 0 to 10 *K-Cups*

> - **Sink**:
>   - Has Handle for on/off


### <u>METHODS OF OBJECTS:</u>
> - **CoffeeMaker**
>   - Can check to see if at least 1 cup of water | BOOL
>   - Displays of enough water is available
>   - Heats water to a 195 | BOOL
>   - Checks to see if *K-Cup* is in | BOOL
>   - Enable and disable brew button | BOOL 
>   - Dispenses coffee into *Mug* | BOOL
>   - Brews coffee | amount dispensed 
>   - can detach water reservoir | BOOL
>   - let *Person* know when 1 cup of coffee is dispensed | BOOL


> - **Person**
>   - Checks if there are *K-Cups* to brew | BOOL
>   - Insert *K-Cup* into *CoffeeMaker** insert |
>   - Select start brewing button | 
>   - See if *CoffeeMaker* needs more water |
>   - Fill resevoir with water from *Sink* | 
>   - Detach resevoir from *CoffeeMaker* |
>   - See if *CoffeeMaker* displays brew complete | BOOL

> - **K-Cup:**
>   - Fits into *CoffeeMaker* K-Cup insert
>   - Accepts water through it to brew coffee

> - **Mug:**
>   - Can accept 1.5 cup of coffee from *CoffeeMaker*
>   - Be picked-up/sat down | STATUS

> - **Sink:**
>   - Can dispense water into reservoir
>   - Turn on/off | STATUS




### <u>LOGIC:</u>