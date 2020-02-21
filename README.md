# Windows Terminal

## My profile
### Sneak Peek
<img src="https://github.com/charlyjose/wt/raw/master/wt.gif">

My WT profile can be found in [profiles.json](https://github.com/charlyjose/wt/blob/master/profiles.json).

## Open Windows Terminal here

#### Setup:
<img src="https://github.com/charlyjose/wt/raw/master/registry.gif">
Run the [wt.reg](https://github.com/charlyjose/wt/blob/master/wt.reg) to add "Open Windows Terminal here" option to your context menu.

#### Context Menu
<img src="https://github.com/charlyjose/wt/raw/master/menu.gif">

### Note
#### Either of the two options work

* "`.`"
* "%`__`CD`__` %"

In [profiles.json](https://github.com/charlyjose/wt/blob/master/profiles.json)

```
{
    ...
    "startingDirectory": ".",
    ...
}
```

OR

```
{
    ...
    "startingDirectory": "%__CD__%",
    ...
}
```