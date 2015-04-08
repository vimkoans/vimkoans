## Basic Mapping

Map the `-` keystroke as delete character and as delete line.

```
:map - x 
```

```
:map - dd
```

## Map special characters

```
:map <space> viw
```

```
:map <c-d> dd
```

## Warning: no comments after mappings

This will cause an error:

```
:map <space> viw " Select word 
```
