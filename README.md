# the-end

Technically, what the most incredible MMO of the world should be

This is a base project that aims to be able to generate and create spells, and skills
based on the player thoughts, fuse spells together, and generate spells with AI based tools.

Eg: create a fireball, fuse this fireball with a spell of wind, fuse it with a cloud of poison
and so on

This project aims to create the spell with the data associated mana consumption, area, damages ...
as well as the sprites, animations, sounds, and everything needed

everything linked to the animation, aoe, sound, design
{
i have no idea, i'll just see what unreal does
}

everything based on game values
<T>{
name: string
description: string
mana cost: number
health cost: number
duration: duration
delay offset: duration
subspells: T[]
}
