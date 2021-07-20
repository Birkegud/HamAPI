# HamAPI
## Usage
```lua
local Domain = "DOMAIN.com"
local URL = "https://www.DOMAIN.com/index.html?Username=Test"
local Response = Ham.GETRequest(URL, Domain)
Response = json.decode(Response)
for k, v in pairs(Response) do
    print(k, v)
end
```