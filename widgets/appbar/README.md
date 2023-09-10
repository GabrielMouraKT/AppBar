# appbar

""
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
""

