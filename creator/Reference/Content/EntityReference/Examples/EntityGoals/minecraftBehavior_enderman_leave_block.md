---
author: v-josjones
ms.author: v-josjones
title: Entity Documentation - minecraft:behavior.enderman_leave_block
ms.prod: gaming
---

# Entity Documentation - minecraft:behavior.enderman_leave_block

`minecraft:behavior.enderman_leave_block` allows the entity to drop the block they are currently holding.

> [!NOTE]
> This behavior can only be used by the `enderman` entity type.

## Example

```json
"minecraft:behavior.enderman_leave_block":{
    "priority": 8,
}
```

## Vanilla entities examples

### enderman

:::code language="json" source="../../../../Source/VanillaBehaviorPack/entities/enderman.json" range="161-163":::

## Vanilla entities using `minecraft:behavior.enderman_leave_block`

- [enderman](../../../../Source/VanillaBehaviorPack_Snippets/entities/enderman.md)
