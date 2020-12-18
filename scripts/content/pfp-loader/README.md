```lua

local Players = game:GetService("Players")
 
--Settings
local userID = 539928638
local cameraAngle = Enum.ThumbnailType.HeadShot
local size = Enum.ThumbnailSize.Size420x420
local url, loaded = Players:GetUserThumbnailAsync(userID, cameraAngle, size)
 
-- Set whatever is the scripts child to the image

item = script:FindFirstChild()
item.Image=url
item.Parent=script.Parent

```
