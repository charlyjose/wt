# Windows Terminal

## My profile
### Sneak Peek
<img src="https://github.com/charlyjose/wt/raw/master/wt.gif">

My WT profile can be found in [profiles.json](https://github.com/charlyjose/wt/blob/master/profiles.json).

## Open Windows Terminal here
### Sneak Peek
<img src="https://github.com/charlyjose/wt/raw/master/menu.gif">

Run the [wt.reg](https://github.com/charlyjose/wt/blob/master/wt.reg) to add "Open Windows Terminal here" option to your context menu.

### Note
#### Either of the two options work

* "."
* "%__CD__%"

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