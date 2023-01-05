Tags: #Dart #Flutter 

## Default Value
Uninitialized variables that have a nullable type have an initial value of `null`. (If you haven’t opted into [null safety](https://dart.dev/null-safety), then every variable has a nullable type.) Even variables with numeric types are initially null, because numbers—like everything else in Dart—are objects.

## Late Variables
When you mark a variable as `late` but initialize it at its declaration, then the initializer runs the first time the variable is used. This lazy initialization is handy in a couple of cases:

-   The variable might not be needed, and initializing it is costly.
-   You’re initializing an instance variable, and its initializer needs access to `this`.
```dart
late String temperature = readTemperature() ;
```

## Final , Const 
use final, const variables to declare a variable whose value is not going to change.

