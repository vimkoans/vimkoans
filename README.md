
## Printing out messages

Print out a message.
```
:echo "Hello, world!"
```

Print out persistent message.
```
:echom "Hello again, world!"
```

Retrieve persisted messages.
```
:messages
```

## Boolean

Line numbers true.
```
:set number
```

Line numbers false.
```
:set nonumber
```

Toggling between true or false.
```
:set number!
```

Ask what an option is currently set to?
```
:set number?
```

Other options?
```
:set wrap?
:set shiftround?
:set matchtime?
```

## Options with values

Syntax: `:set <name>=<value>`.

```
:set numberwidth=10
:set numberwidth=4
:set numberwidth?
```

## Set multiple options at once

```
:set number numberwidth=6
```

