# Task #5
### @flyoutOnly true
### @hideIteration true
### @explicitHints false

``` ghost
    for (let index = 0; index < 1; index++) {
        agent.move(FORWARD, 1)
    }
```
```template
   //     
```

## Gather food and place it into the Chef AI Robot

Navigate the Agent through the maze. Gather all the food you can find and place it into the Chef AI Robot. If items disappear from ground, use button next to Chef AI Robot.

### ~ Hint 1

In this task you must collect 8 food items. In first round you need collect: ``||Onion||``, ``||Grapes||``, ``||Sausage||``, ``||Chocolate||``. In next round you will need collect: ``||Meat||``, ``||Peas|``, ``||Tomato||``, ``||Garlic||``. If you make a mistake, feel free to click the "reset Agent position" button positioned near Chef AI Robot.

### ~ Hint 2
Once you have obtained all the food items after a given round, right-click on the Agent to transfer the acquired food to the Chef AI Robot by also right-clicking on it. Good luck!


```typescript-valid
First round solution for collecting 4 items
```
``` blocks
agent.move(FORWARD, 3)
agent.collectAll()
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 2)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 4)
agent.collectAll()
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 2)
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 2)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 3)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 2)
agent.collectAll()
agent.move(BACK, 6)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 2)
agent.collectAll()
```
```
```
```typescript-valid
Second round solution for collecting 4 items
```
``` blocks
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 3)
agent.collectAll()
agent.move(FORWARD, 4)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 2)
agent.collectAll()
agent.move(FORWARD, 2)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 3)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 2)
agent.collectAll()
agent.move(BACK, 3)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 3)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 2)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 5)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 4)
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 2)
agent.collectAll()
```
```package
github:kwakong/ai-cosmic_coding_at_university
```
