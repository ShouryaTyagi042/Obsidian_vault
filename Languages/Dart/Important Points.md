Tags : #Dart #Flutter 

```dart
void printInteger(int aNumber) {
	print('The number is $aNumber') ;
}
void main() {
	var number = 42 ;
	printInteger(number) ;
}
```

`var`
A way to declare a variable without specifying its type. The type of this variable (`int`) is determined by its initial value.

>[!tip]
>Unlike Java, Dart doesn’t have the keywords `public`, `protected`, and `private`. If an identifier starts with an underscore (`_`), it’s private to its library.

====Every variable in dart refers to an object .==
