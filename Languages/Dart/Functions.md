Tags: #Dart #Flutter 

## Shorthand Functions

```DART
bool isNoble(int noble_number) => _nobleGases[noble_number] != null;
```

The `=> _expr_` syntax is a shorthand for `{ return _expr_; }`.

# Parameters

## Optional & Required 
Optional parameters can be added by using [] brackets , whereas by adding the 'required' keyword -> required parameters can be added.

## Anonymous Functions

```DART
	const list = ['apples', 'oranges', 'bananas'];

	list

		.map((item) => item.toUpperCase())

		.forEach((item) => print('$item : ${item.length}'));
```

## Lexical Closures & Scopes

A _closure_ is a function object that has access to variables in its lexical scope, even when the function is used outside of its original scope

