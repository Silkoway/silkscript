# Ideas
## Standard Librarys
### minecraft
.commandname
All of the commands
ENTITY.name
ITEM.name
## statements
```
if (coins=) {
    
}
```
## variables
string var = "this"

~~String->binary->int~~

~~base like 33+48+10 so base 92 number
somehow make a power function~~
make invisible armor stand with tag of [variable name] and tag "variable", name is the value.
make armor stand in sky invulnarable
reserve variable name "variable"

num var = 10

Use invisible scoreboard variables

## conditions

make like a function that like
1. makes a copy of first value
2. subtracts second from first
3. checks if output is equal to smth
if end == 0 then `==`
if end > 0 then `<`
if end < 0 then `>`

# Example Code
### buycoin.mcs
```
get coins from 'stats.mcs'
if (coins >= 50) {
    coins -= 50
    summon(ENTITY.sheep)
}



```
