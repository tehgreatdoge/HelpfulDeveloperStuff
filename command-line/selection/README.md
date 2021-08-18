# Selection
perform edits to your selection
*Add CollectionService Tags*
```lua
Tag = ""; --[[EndOfSettings]] H=game:GetService("ChangeHistoryService");S=game.Selection:Get();C=game:GetService("CollectionService");H:SetWaypoint("TagAddStart") for k,v in pairs(S)do C:AddTag(v,Tag) end H:SetWaypoint("TagAddEnd")
```
