# 2CS Flutter Convention

# Naming

### Bloc

##### Bloc Events

- Start with verb 
- End with suffix **Event**

Example:
```
- ToDosEvent
- LoadToDosEvent
- DeleteToDoEvent
```

##### Bloc States

Example:
```
- Loading
- Loaded
- LoadFailed
```


### Extensions:

| Tables   |Are			                 |
|----------|:---------------------------|
| Folder   |`/common/extensions/` 	    | 
| File name |Same as `class_name` with is written extension. Exp: `date_time.dart` | 
| Extension name |Add `extension` as suffix, Exp: `DateTimeExtension` | 

# Coding
### Linebreak:
Leaf elemenent: (params < 2 && column < 140): inline. and inverse.

### Depth tree: 
Maximum: 5

### Require & Assert
Always use pair of `@require` & `:assert`.

### TextTheme
| Tables   |Are.                                                            |
|----------|:---------------------------------------------------------------|
| Headline |Large text than title                                           | 
| Title    |    Title text of appbar, dialog                                | 
| Subhead  | Primary text in list                                           |
| Body1.   | Default text                                                   |
| Body2.   | Emphasizing text that would otherwise be [body1]               |
| Caption. | Small text like caption                                        |
| Subtitle | For medium emphasis text that's a little smaller than [subhead]|
| Overline | Typically used for captions or to introduce a (larger) headline|
  
### Functions ordering
```
Function A() {
  B();
  D();
}

Function B() {
  E();
}

Function E() {
}

Function D() {
}

Function C() {
}

FunctionF() {
 E()
}
```
# Branch name:
```
- feature/192390_feature_name

- hotfix/134233_hotfix_name

- release/1.0.130
```

# Release:

### Version number, buildNunber:
```
- Version: 1.2
- iOS BuildNumber	: 1.2.YYMMDDhhm
- Android Build.    : YYMMDDhhm
```