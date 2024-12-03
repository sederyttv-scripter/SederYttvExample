SederYttv UI Library
This is a simple UI library for Roblox to help you create customizable, interactive UIs with ease. It allows you to add elements like windows, sections, sliders, toggles, buttons, and more!

Installation
To use this library, simply load it into your script by running:
local UILib = loadstring(game:HttpGet("https://raw.githubusercontent.com/sederyttv-scripter/Sprunki/refs/heads/main/Proers"))()

## **Window Example**

Here's an example of how to create a basic window using the library:

```lua
-- Load the UI Library
local window = UILibrary:NewWindow("My UI Window")

-- Optionally, you can add sections, buttons, sliders, etc. to this window
-- For now, we're just creating a simple window
