# Orc Battle Game

In the game, you are a knight surrounded by 12 monsters, engaged in a fight to
the death. With your superior wits and your repertoire of sword-fighting maneuvers,
you must carefully strategize in your battle with orcs, hydras, and other nasty
enemies. One wrong move and you may be unable to kill them all before being worn
down by their superior numbers.

## Game Play

    [1]> (load "main.cl")
    ;; Loading file main.cl ...
    ;; Loaded file main.cl
    T
    [2]> (orc-battle)
    You are a valiant knight with a health of 30, an agility of 30, and a strength of 30
    Your foes:
       1. (Health=4) A slime mold with a sliminess of 5
       2. (Health=7) A slime mold with a sliminess of 5
       3. (Health=7) A wicked orc with a level 5 club
       4. (Health=9) A slime mold with a sliminess of 4
       5. (Health=10) A malicious hydra with 10 heads.
       6. (Health=1) A fierce BRIGAND
       7. (Health=6) A fierce BRIGAND
       8. (Health=2) A malicious hydra with 2 heads.
       9. (Health=6) A slime mold with a sliminess of 2
       10. (Health=5) A wicked orc with a level 5 club
       11. (Health=8) A slime mold with a sliminess of 1
       12. (Health=9) A fierce BRIGAND
    Attack style: [s]tab [d]ouble swing [r]oundhouse:s
    Monster #:5
    The corpse of the fully decapitated and decapacitated hydra falls to the floor!
    Your foes:
       1. (Health=4) A slime mold with a sliminess of 5
       2. (Health=7) A slime mold with a sliminess of 5
       3. (Health=7) A wicked orc with a level 5 club
       4. (Health=9) A slime mold with a sliminess of 4
       5. **dead**
       6. (Health=1) A fierce BRIGAND
       7. (Health=6) A fierce BRIGAND
       8. (Health=2) A malicious hydra with 2 heads.
       9. (Health=6) A slime mold with a sliminess of 2
       10. (Health=5) A wicked orc with a level 5 club
       11. (Health=8) A slime mold with a sliminess of 1
       12. (Health=9) A fierce BRIGAND
    Attack style: [s]tab [d]ouble swing [r]oundhouse:s
    Monster #:12
    You hit the BRIGAND, knocking off 5 health points!
    Your foes:
       1. (Health=4) A slime mold with a sliminess of 5
       2. (Health=7) A slime mold with a sliminess of 5
       3. (Health=7) A wicked orc with a level 5 club
       4. (Health=9) A slime mold with a sliminess of 4
       5. **dead**
       6. (Health=1) A fierce BRIGAND
       7. (Health=6) A fierce BRIGAND
       8. (Health=2) A malicious hydra with 2 heads.
       9. (Health=6) A slime mold with a sliminess of 2
       10. (Health=5) A wicked orc with a level 5 club
       11. (Health=8) A slime mold with a sliminess of 1
       12. (Health=4) A fierce BRIGAND
    Attack style: [s]tab [d]ouble swing [r]oundhouse:s
    Monster #:4
    You hit the SLIME-MOLD, knocking off 7 health points!
    An orc swings his club at you and knocks off 2 of your health points. A brigand catches your leg with his whip, taking off 2 agility points! A brigand cuts your arm with his whip, taking off 2 strength points! A hydra attacks you with 1 of its heads! It also grows back one more head! An orc swings his club at you and knocks off 4 of your health points. A brigand catches your leg with his whip, taking off 2 agility points!
    You are a valiant knight with a health of 23, an agility of 26, and a strength of 28
    Your foes:
       1. (Health=4) A slime mold with a sliminess of 5
       2. (Health=7) A slime mold with a sliminess of 5
       3. (Health=7) A wicked orc with a level 5 club
       4. (Health=2) A slime mold with a sliminess of 4
       5. **dead**
       6. (Health=1) A fierce BRIGAND
       7. (Health=6) A fierce BRIGAND
       8. (Health=3) A malicious hydra with 3 heads.
       9. (Health=6) A slime mold with a sliminess of 2
       10. (Health=5) A wicked orc with a level 5 club
       11. (Health=8) A slime mold with a sliminess of 1
       12. (Health=4) A fierce BRIGAND
    Attack style: [s]tab [d]ouble swing [r]oundhouse:d
    Your double swing has a strength of 1
    Monster #:2
    You hit the SLIME-MOLD, knocking off 1 health points!
    Monster #:3
    You hit the ORC, knocking off 1 health points!
    Your foes:
       1. (Health=4) A slime mold with a sliminess of 5
       2. (Health=6) A slime mold with a sliminess of 5
       3. (Health=6) A wicked orc with a level 5 club
       4. (Health=2) A slime mold with a sliminess of 4
       5. **dead**
       6. (Health=1) A fierce BRIGAND
       7. (Health=6) A fierce BRIGAND
       8. (Health=3) A malicious hydra with 3 heads.
       9. (Health=6) A slime mold with a sliminess of 2
       10. (Health=5) A wicked orc with a level 5 club
       11. (Health=8) A slime mold with a sliminess of 1
       12. (Health=4) A fierce BRIGAND
    Attack style: [s]tab [d]ouble swing [r]oundhouse:s
    Monster #:11
    You killed the SLIME-MOLD!
    An orc swings his club at you and knocks off 1 of your health points. A brigand cuts your arm with his whip, taking off 2 strength points! A brigand catches your leg with his whip, taking off 2 agility points! A hydra attacks you with 1 of its heads! It also grows back one more head! An orc swings his club at you and knocks off 4 of your health points. A brigand cuts your arm with his whip, taking off 2 strength points!
    You are a valiant knight with a health of 17, an agility of 24, and a strength of 24
    Your foes:
       1. (Health=4) A slime mold with a sliminess of 5
       2. (Health=6) A slime mold with a sliminess of 5
       3. (Health=6) A wicked orc with a level 5 club
       4. (Health=2) A slime mold with a sliminess of 4
       5. **dead**
       6. (Health=1) A fierce BRIGAND
       7. (Health=6) A fierce BRIGAND
       8. (Health=4) A malicious hydra with 4 heads.
       9. (Health=6) A slime mold with a sliminess of 2
       10. (Health=5) A wicked orc with a level 5 club
       11. **dead**
       12. (Health=4) A fierce BRIGAND
    Attack style: [s]tab [d]ouble swing [r]oundhouse:d
    Your double swing has a strength of 4
    Monster #:2
    You hit the SLIME-MOLD, knocking off 4 health points!
    Monster #:3
    You hit the ORC, knocking off 4 health points!
    Your foes:
       1. (Health=4) A slime mold with a sliminess of 5
       2. (Health=2) A slime mold with a sliminess of 5
       3. (Health=2) A wicked orc with a level 5 club
       4. (Health=2) A slime mold with a sliminess of 4
       5. **dead**
       6. (Health=1) A fierce BRIGAND
       7. (Health=6) A fierce BRIGAND
       8. (Health=4) A malicious hydra with 4 heads.
       9. (Health=6) A slime mold with a sliminess of 2
       10. (Health=5) A wicked orc with a level 5 club
       11. **dead**
       12. (Health=4) A fierce BRIGAND
    Attack style: [s]tab [d]ouble swing [r]oundhouse:d
    Your double swing has a strength of 3
    Monster #:7
    You hit the BRIGAND, knocking off 3 health points!
    Monster #:9
    You hit the SLIME-MOLD, knocking off 3 health points!
    An orc swings his club at you and knocks off 1 of your health points. A brigand catches your leg with his whip, taking off 2 agility points! A brigand cuts your arm with his whip, taking off 2 strength points! A hydra attacks you with 2 of its heads! It also grows back one more head! An orc swings his club at you and knocks off 1 of your health points. A brigand catches your leg with his whip, taking off 2 agility points!
    You are a valiant knight with a health of 13, an agility of 20, and a strength of 22
    Your foes:
       1. (Health=4) A slime mold with a sliminess of 5
       2. (Health=2) A slime mold with a sliminess of 5
       3. (Health=2) A wicked orc with a level 5 club
       4. (Health=2) A slime mold with a sliminess of 4
       5. **dead**
       6. (Health=1) A fierce BRIGAND
       7. (Health=3) A fierce BRIGAND
       8. (Health=5) A malicious hydra with 5 heads.
       9. (Health=3) A slime mold with a sliminess of 2
       10. (Health=5) A wicked orc with a level 5 club
       11. **dead**
       12. (Health=4) A fierce BRIGAND
    Attack style: [s]tab [d]ouble swing [r]oundhouse:s
    Monster #:8
    The corpse of the fully decapitated and decapacitated hydra falls to the floor!
    Your foes:
       1. (Health=4) A slime mold with a sliminess of 5
       2. (Health=2) A slime mold with a sliminess of 5
       3. (Health=2) A wicked orc with a level 5 club
       4. (Health=2) A slime mold with a sliminess of 4
       5. **dead**
       6. (Health=1) A fierce BRIGAND
       7. (Health=3) A fierce BRIGAND
       8. **dead**
       9. (Health=3) A slime mold with a sliminess of 2
       10. (Health=5) A wicked orc with a level 5 club
       11. **dead**
       12. (Health=4) A fierce BRIGAND
    Attack style: [s]tab [d]ouble swing [r]oundhouse:r
    You hit the ORC, knocking off 1 health points! You killed the ORC! You hit the SLIME-MOLD, knocking off 1 health points! You hit the SLIME-MOLD, knocking off 1 health points! You hit the ORC, knocking off 1 health points! You killed the SLIME-MOLD!
    A brigand cuts your arm with his whip, taking off 2 strength points! A brigand catches your leg with his whip, taking off 2 agility points! An orc swings his club at you and knocks off 2 of your health points. A brigand cuts your arm with his whip, taking off 2 strength points!
    You are a valiant knight with a health of 11, an agility of 18, and a strength of 18
    Your foes:
       1. (Health=4) A slime mold with a sliminess of 5
       2. (Health=2) A slime mold with a sliminess of 5
       3. **dead**
       4. **dead**
       5. **dead**
       6. (Health=1) A fierce BRIGAND
       7. (Health=3) A fierce BRIGAND
       8. **dead**
       9. (Health=2) A slime mold with a sliminess of 2
       10. (Health=4) A wicked orc with a level 5 club
       11. **dead**
       12. (Health=4) A fierce BRIGAND
    Attack style: [s]tab [d]ouble swing [r]oundhouse:r
    You hit the SLIME-MOLD, knocking off 1 health points! You hit the ORC, knocking off 1 health points! You hit the ORC, knocking off 1 health points!
    Your foes:
       1. (Health=3) A slime mold with a sliminess of 5
       2. (Health=2) A slime mold with a sliminess of 5
       3. **dead**
       4. **dead**
       5. **dead**
       6. (Health=1) A fierce BRIGAND
       7. (Health=3) A fierce BRIGAND
       8. **dead**
       9. (Health=2) A slime mold with a sliminess of 2
       10. (Health=2) A wicked orc with a level 5 club
       11. **dead**
       12. (Health=4) A fierce BRIGAND
    Attack style: [s]tab [d]ouble swing [r]oundhouse:r
    You hit the BRIGAND, knocking off 1 health points! You hit the SLIME-MOLD, knocking off 1 health points! You killed the BRIGAND! You hit the SLIME-MOLD, knocking off 1 health points!
    A brigand catches your leg with his whip, taking off 2 agility points! An orc swings his club at you and knocks off 1 of your health points. A brigand cuts your arm with his whip, taking off 2 strength points!
    You are a valiant knight with a health of 10, an agility of 16, and a strength of 16
    Your foes:
       1. (Health=1) A slime mold with a sliminess of 5
       2. (Health=2) A slime mold with a sliminess of 5
       3. **dead**
       4. **dead**
       5. **dead**
       6. **dead**
       7. (Health=3) A fierce BRIGAND
       8. **dead**
       9. (Health=2) A slime mold with a sliminess of 2
       10. (Health=2) A wicked orc with a level 5 club
       11. **dead**
       12. (Health=3) A fierce BRIGAND
    Attack style: [s]tab [d]ouble swing [r]oundhouse:d
    Your double swing has a strength of 1
    Monster #:12
    You hit the BRIGAND, knocking off 1 health points!
    Monster #:7
    You hit the BRIGAND, knocking off 1 health points!
    Your foes:
       1. (Health=1) A slime mold with a sliminess of 5
       2. (Health=2) A slime mold with a sliminess of 5
       3. **dead**
       4. **dead**
       5. **dead**
       6. **dead**
       7. (Health=2) A fierce BRIGAND
       8. **dead**
       9. (Health=2) A slime mold with a sliminess of 2
       10. (Health=2) A wicked orc with a level 5 club
       11. **dead**
       12. (Health=2) A fierce BRIGAND
    Attack style: [s]tab [d]ouble swing [r]oundhouse:r
    You hit the BRIGAND, knocking off 1 health points! You hit the SLIME-MOLD, knocking off 1 health points!
    A brigand catches your leg with his whip, taking off 2 agility points! An orc swings his club at you and knocks off 4 of your health points. A brigand cuts your arm with his whip, taking off 2 strength points!
    You are a valiant knight with a health of 6, an agility of 14, and a strength of 14
    Your foes:
       1. (Health=1) A slime mold with a sliminess of 5
       2. (Health=2) A slime mold with a sliminess of 5
       3. **dead**
       4. **dead**
       5. **dead**
       6. **dead**
       7. (Health=2) A fierce BRIGAND
       8. **dead**
       9. (Health=1) A slime mold with a sliminess of 2
       10. (Health=2) A wicked orc with a level 5 club
       11. **dead**
       12. (Health=1) A fierce BRIGAND
    Attack style: [s]tab [d]ouble swing [r]oundhouse:r
    You killed the SLIME-MOLD! You killed the BRIGAND! You hit the ORC, knocking off 1 health points! You hit the SLIME-MOLD, knocking off 1 health points! You killed the ORC!
    A brigand catches your leg with his whip, taking off 2 agility points!
    You are a valiant knight with a health of 6, an agility of 12, and a strength of 14
    Your foes:
       1. (Health=1) A slime mold with a sliminess of 5
       2. (Health=1) A slime mold with a sliminess of 5
       3. **dead**
       4. **dead**
       5. **dead**
       6. **dead**
       7. (Health=2) A fierce BRIGAND
       8. **dead**
       9. **dead**
       10. **dead**
       11. **dead**
       12. **dead**
    Attack style: [s]tab [d]ouble swing [r]oundhouse:r
    You hit the BRIGAND, knocking off 1 health points! You killed the SLIME-MOLD! You killed the SLIME-MOLD! You killed the BRIGAND!
    Congratulations! You have vanquished all of your foes.
    "Congratulations! You have vanquished all of your foes."
    
