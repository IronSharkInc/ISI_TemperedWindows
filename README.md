# ISI Tempered Windows

Makes windows 100x stronger. Still weaker than normal blocks (they are windows after all), but now they won't shatter when a zombie sneezes.

## Numbers

|                    | frameshape | wood      | cobblestone | concrete | steel |
|--------------------|:----------:|:---------:|:-----------:|:--------:|:-----:|
| **windows before** | 1 (*0.1*)  | 1 (*0.5*) | 2 (*1.5*)   | 5        | 10    |
| **windows after**  | 10         | 50        | 150         | 500      | 1000  |
| **normal blocks**  | 100        | 500       | 1500        | 5000     | 10000 |

*Values in parentheses are the raw numbers. In game they are rounded up to the nearest whole number.*

## Before

![before frameshape](images/before/1-frameshape.png)
![before wood](images/before/2-wood.png)
![before cobblestone](images/before/3-cobblestone.png)
![before concrete](images/before/4-concrete.png)
![before steel](images/before/5-steel.png)

## After

![after frameshape](images/after/1-frameshape.png)
![after wood](images/after/2-wood.png)
![after cobblestone](images/after/3-cobblestone.png)
![after concrete](images/after/4-concrete.png)
![after steel](images/after/5-steel.png)

## Normal

![normal frameshape](images/normal/1-frameshape.png)
![normal wood](images/normal/2-wood.png)
![normal cobblestone](images/normal/3-cobblestone.png)
![normal concrete](images/normal/4-concrete.png)
![normal steel](images/normal/5-steel.png)

## Testing

1. Grab a stack of frameshapes, wood, cobblestone rocks, concrete mix, forged steel, and a nailgun
2. Place 5 windows and upgrade to get one of each type
3. Shoot each window once with nailgun
4. Verify HP values match table:

| Window Type | Expected HP |
|-------------|-------------|
| Frameshape  | 10          |
| Wood        | 50          |
| Cobblestone | 150         |
| Concrete    | 500         |
| Steel       | 1000        |
