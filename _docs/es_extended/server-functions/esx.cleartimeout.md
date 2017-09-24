---
title: ESX.ClearTimeout
category: ES Extended
order: 3
---

```lua
local id = ESX.SetTimeout(5000, function()
  print('it will never show')
end)

ESX.ClearTimeout(id)
```

Clear a timeout callback