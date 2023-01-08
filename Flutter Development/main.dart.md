tags : #Dart #Flutter 
links:

```Dart
void main() {
  runApp(MyApp()) ;
}
```

```dart
class MyApp extends StatelessWidget {  
	const MyApp({super.key});  
@override  
Widget build(BuildContext context) {    
	return ChangeNotifierProvider(      
		create: (context) => MyAppState(),      
		child: MaterialApp(        
			title: 'Namer App',        
			theme: ThemeData(          useMaterial3: true,          
			colorScheme: ColorScheme.fromSeed(seedColor: Colors.green),        ),        
			home: MyHomePage(),      ),    );  }}
```

The `MyApp` class extends `StatelessWidget`. Widgets are the elements from which you build every Flutter app. As you can see, even the _app itself_ is a widget.

The code in `MyApp` sets up the whole app. It creates the app-wide state (more on this later), names the app, defines the visual theme, and sets the "home" widget—the starting point of your app.

Refer to this for more info : [lib/main.dart]([Your first Flutter app (google.com)](https://codelabs.developers.google.com/codelabs/flutter-codelab-first#3))
