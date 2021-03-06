# Experience Hooks

## CanSpendXp

``` csharp
bool CanSpendXp(ulong id, float amount) 
{
    Puts("CanSpendXp works!");
    return true;
}
```

``` lua
function PLUGIN:CanSpendXp(id, amount)
    print("CanSpendXp works!")
end
```

``` javascript
CanSpendXp: function(id, turret) {
    print("CanSpendXp works!");
}
```

``` coffeescript
We need a CoffeeScript example here
```

``` python
def CanSpendXp(self, id, turret):
    print "CanSpendXp works!"
```

 * Called when a player attempts to spend XP
 * Returning true/false overrides default behavior

## OnXpEarn

``` csharp
object OnXpEarn(ulong id, float amount, string source)
{
    Puts("OnXpEarn works!");
    return 1f;
}
```

``` lua
function PLUGIN:OnXpEarn(id, info)
    print("OnXpEarn works!")
end
```

``` javascript
OnXpEarn: function(id, info) {
    print("OnXpEarn works!");
}
```

``` coffeescript
We need a CoffeeScript example here
```

``` python
def OnXpEarn(self, id, info):
    print "OnXpEarn works!"
```

 * Called before XP is earned by the player
 * Returning a float overrides the default amount

## OnXpEarned

``` csharp
void OnXpEarned(ulong id, float amount, string source)
{
    Puts("OnXpEarned works!");
}
```

``` lua
function PLUGIN:OnXpEarned(connection)
    print("OnXpEarned works!")
end
```

``` javascript
OnXpEarned: function(connection) {
    print("OnXpEarned works!");
}
```

``` coffeescript
We need a CoffeeScript example here
```

``` python
def OnXpEarned(self, connection):
    print "OnXpEarned works!"
```

 * Called after XP is earned by the player
 * No return behavior

## OnXpReset

``` csharp
void OnXpReset(BasePlayer player)
{
    Puts("OnXpReset works!");
}
```

``` lua
function PLUGIN:OnXpReset(connection)
    print("OnXpReset works!")
end
```

``` javascript
OnXpReset: function(connection) {
    print("OnXpReset works!");
}
```

``` coffeescript
We need a CoffeeScript example here
```

``` python
def OnXpReset(self, connection):
    print "OnXpReset works!"
```

 * Called when XP is reset for the player
 * No return behavior

## OnXpSet

``` csharp
void OnXpSet(ulong id, float amount)
{
    Puts("OnXpSet works!");
}
```

``` lua
function PLUGIN:OnXpSet(connection)
    print("OnXpSet works!")
end
```

``` javascript
OnXpSet: function(connection) {
    print("OnXpSet works!");
}
```

``` coffeescript
We need a CoffeeScript example here
```

``` python
def OnXpSet(self, connection):
    print "OnXpSet works!"
```

 * Called when XP is set for the player
 * No return behavior

## OnXpSpent

``` csharp
void OnXpSpent(ulong id, float amount)
{
    Puts("OnXpSpent works!");
}
```

``` lua
function PLUGIN:OnXpSpent(connection)
    print("OnXpSpent works!")
end
```

``` javascript
OnXpSpent: function(connection) {
    print("OnXpSpent works!");
}
```

``` coffeescript
We need a CoffeeScript example here
```

``` python
def OnXpSpent(self, connection):
    print "OnXpSpent works!"
```

 * Called when XP has been spent by the player
 * No return behavior
