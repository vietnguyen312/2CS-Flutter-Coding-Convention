# 2CS-Flutter-Coding-Convention

# Naming

#### Bloc Events

- Start with verb 
- End with suffix **Event**

Example:
```
- ToDosEvent
- LoadToDosEvent
- DeleteToDoEvent
```

#### Bloc States

Example:
```
- Loading
- Loaded
- LoadFailed
```
# Functions ordering
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
