<script setup>
import CraftingGui from './components/CraftingGui.vue'
</script>

# Quiver
Quiver is an item that can store arrow inside and select which arrow to use. It can be bound to Chestplate or Leggings to make it possible to use Quiver while armor is equipped.

## Obtaining
Quiver can be crafted in crafting table.

<CraftingGui
slot_1="minecraft:leather"
slot_2=""
slot_3="minecraft:leather"
slot_4="minecraft:leather"
slot_5="minecraft:chest"
slot_6="minecraft:leather"
slot_7="minecraft:leather"
slot_8="minecraft:leather"
slot_9="minecraft:leather"
output="mod:quiver"
output_count="1"
/>

### Coloring
Quiver can be dyed like Leather Armor, you can use this [calculator](https://minecraft.wiki/w/Calculators/Armor_color) to check the dyeing sequence based on the color you want.

## Usage
There are a few different situations and ways to access a Quiver Menu. The selected slot will be surrounded with orange border.

![Quiver Menu](/quiver_screen.png)

### Holding Quiver Item
If you are holding a Quiver Item or a Chestplates/Leggings that bound with a Quiver Item, Quiver Menu can be accessed by using (Right Click) the item.

### Equipped Quiver
If Quiver is equipped in chest slot or Chestplates/Leggings that bound with Quiver is equipped, you can access the Quiver Menu with keybind, default key is `R`.

::: warning Important Notes
If both Chestplates and Leggings are bound with Quiver and equipped, the mod will always use Chestplates first.
:::

### Selecting Slot
Quiver Slot can be selected by pressing number key `1-9` when Quiver Menu is open or scrolling with mouse wheel.

If the selected slot doesn't have any arrow, it will use vanilla logic to search for arrow (inventory).