# FlutterSpace
Flutter Projects Widgets
#App Bar
![image](https://github.com/GabrielMouraKT/FlutterSpace/assets/69040085/b882f092-0779-4540-8a5d-b08133780294)
````
import 'package:flutter/material.dart';

void main() {
  runApp(const MyApp());
}

class MyApp extends StatelessWidget {
  const MyApp({super.key});

  // This widget is the root of your application.   
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      debugShowCheckedModeBanner: false,
      home: Scaffold(
        backgroundColor: Colors.deepPurple[200],
        appBar: AppBar(
          elevation: 0,
          backgroundColor: Colors.deepPurple[500],
          title: Center(
            child: Text('A P P B A R'),
          ),
        ),
      ),
    );
  }
}
//@GabrielMouraKT
````



