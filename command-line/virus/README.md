#Copy-Paste
* **Find requires**
```lua
a=workspace:GetDescendants(); b = 0; c=0 for k,v in pairs(a) do if v:IsA('Script') then b = b+1 if string.find(v.Source,"require") then print(v:GetFullName()) c = c+1 end end end warn("\n ------------ \n RESULTS \n ------------ \n"..b.." scripts found \n"..c.." requires found in scripts")
```
