# realms-library-
# Aviso ⚠️ realms library está na sua 1° versão, e pode conter bugs 
# Além disso lembre-se de por o nome da tab que fica seu botão ou toggle 
# criando a library:
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/lucaszedamanga/realms-library-/refs/heads/main/Protected_4068189292969153.lua.txt"))()
```

# Botando a library:

```lua
create_library({
Name = "Name da library"
})
```

# Criando uma tab
```lua
create_tab({Name = "tab name"})
```

# criando um botão 

```lua
create_button({
tab = "nome da tab",
Name = "nome do botão", 
Callback = function()
print("alien é bixa")
end
})
```
# criando uma toggle
```lua
local loop = false
create_button({
tab = "Outros",
Name = "Tp to spawn", 
Callback = function()
loop = not loop
while loop do 
if loop then
wait(0.01)
print("alien é bixa")
end
end
end
})
```

# criando uma check list
```lua

create_checklist({
Name = "your name  here",
tab = "Outros",
things = {"maçã", "pêra", "melancia", "uva"},
Callback = function(value)
print(value)
end
})
```
