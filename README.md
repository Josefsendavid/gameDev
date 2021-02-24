Hierachi & Scene structure

I vores spil har jeg lavet parent-object af checkpoints,
"deathfloors" og objects til at ødelægge et gammelt checkpoint,
hvis man når til næste checkpoint i spillet.
På den måde vil vores projekt være mere struktureret,
så der ikke ligger mange ens objekter i roden og flyder.


Colliders & Triggers

Til checkpoints har jeg taget brug af colliders & triggers,
så når player collider med et bestemt object,
vil det tilhørende script blive triggered.
I dette spil er et af vores trigger scripts: player.transform.position og player.transform.rotation,
som gør at når objektet med tagget "player" collider med "deathfloor",
vil player objektets position blive flyttet til deathfloors tilhørende checkpoint.
