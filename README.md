local Games = loadstring(game:HttpGet("https://raw.githubusercontent.com/bac1916r30-a11y/V1/refs/heads/main/README.md"))()

local URL = Games[game.PlaceId]

if URL then
  loadstring(game:HttpGet(URL))()
end
