# Day 1 Events Challenge

```template
blocks.place(LIGHT_GRAY_GLAZED_TERRACOTTA, world(0, 4, 0))
blocks.onBlockPlaced(GRASS, function () {
    blocks.place(GREEN_GLAZED_TERRACOTTA, world(20, 4, 0))
})
blocks.onBlockBroken(LOG_OAK, function () {
    blocks.place(BLUE_GLAZED_TERRACOTTA, world(12, 4, 0))
})
player.onItemInteracted(DIAMOND_SWORD, function () {
    blocks.place(ORANGE_GLAZED_TERRACOTTA, world(4, 4, 0))
})
player.onChat("run", function () {
    blocks.place(YELLOW_GLAZED_TERRACOTTA, world(16, 4, 0))
})
player.onTravelled(RIDING, function () {
    blocks.place(RED_GLAZED_TERRACOTTA, world(8, 4, 0))
})
```

## Events Challenge

In this activity, you will learn about events by trying to guess what block will be placed when certain events happen in the world.

## Station 1

The ``||loops.on start||`` event has a ``||blocks.place block at||`` block inside! What block do you think will be placed when the code starts? Press the Green Play arrow to find out!

```blocks
blocks.place(LIGHT_GRAY_GLAZED_TERRACOTTA, world(0, 4, 0))
```

## Station 2

Can you find the ``||player.on item used||`` event? What block is going to be placed?

```blocks
player.onItemInteracted(DIAMOND_SWORD, function () {
    blocks.place(ORANGE_GLAZED_TERRACOTTA, world(4, 4, 0))
})
```

## Station 3

Can you find the ``||player.on player riding||`` event? What block is going to be placed?

```blocks
player.onTravelled(RIDING, function () {
    blocks.place(RED_GLAZED_TERRACOTTA, world(8, 4, 0))
})
```

## Station 4

Can you find the ``||blocks.on block broken||`` event? What block is going to be placed?

```blocks
blocks.onBlockBroken(LOG_OAK, function () {
    blocks.place(BLUE_GLAZED_TERRACOTTA, world(12, 4, 0))
})
```

## Station 5

Can you find the ``||player.on chat command||`` event? What block is going to be placed?

```blocks
player.onChat("run", function () {
    blocks.place(YELLOW_GLAZED_TERRACOTTA, world(16, 4, 0))
})
```

## Station 6

Can you find the ``||blocks.on block placed||`` event? What block is going to be placed?

```blocks
blocks.onBlockPlaced(GRASS, function () {
    blocks.place(GREEN_GLAZED_TERRACOTTA, world(20, 4, 0))
})
```

## Activity Complete!

You did it! You learned about several different events and how we can run code when those events occur!
