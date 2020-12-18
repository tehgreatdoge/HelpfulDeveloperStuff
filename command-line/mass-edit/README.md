#Copy-Paste
* **Approximate Snap-to-grid**
```lua
items=workspace:GetDescendants(); for i=1,#items do if items[i]:IsA("Part") then items[i].Position = Vector3.new(items[i].Position.X-items[i].Position.X%0.125,items[i].Position.Y-items[i].Position.Y%0.125,items[i].Position.Z-items[i].Position.Z%0.125) items[i].Size  = Vector3.new(items[i].Size.X-items[i].Size.X%0.125,items[i].Size.Y-items[i].Size.Y%0.125,items[i].Size.Z-items[i].Size.Z%0.125)end end
```
