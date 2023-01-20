Tags :  #Dart #Flutter 
Links : [[State Class]]

Widgets are the central class hierarchy in the Flutter framework. A widget is an immutable description of part of a user interface. Widgets can be inflated into elements, which manage the underlying render tree.

-   [StatefulWidget](https://api.flutter.dev/flutter/widgets/StatefulWidget-class.html) and [State](https://api.flutter.dev/flutter/widgets/State-class.html), for widgets that can build differently several times over their lifetime.
-   [InheritedWidget](https://api.flutter.dev/flutter/widgets/InheritedWidget-class.html), for widgets that introduce ambient state that can be read by descendant widgets.
-   [StatelessWidget](https://api.flutter.dev/flutter/widgets/StatelessWidget-class.html), for widgets that always build the same way given a particular configuration and ambient state.