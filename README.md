-- Create a new part
local hat = Instance.new("Part")
hat.Name = "CoolHat"
hat.Size = Vector3.new(2, 1, 2) -- Adjust the size as needed
hat.BrickColor = BrickColor.new("Bright blue") -- Change color as desired
hat.Position = Vector3.new(0, 10, 0) -- Adjust the position as needed
hat.Anchored = true -- So the hat doesn't fall down
hat.CanCollide = false -- So the hat doesn't block players
hat.Parent = game.Workspace -- Put the hat in the workspace
