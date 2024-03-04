import 'package:flutter/material.dart';

const Color darkBlue = Color.fromARGB(255, 18, 32, 47);

void main() {
  runApp(MyApp());
}

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      theme: ThemeData.dark().copyWith(
        scaffoldBackgroundColor: darkBlue,
      ),
      debugShowCheckedModeBanner: false,
      home: Scaffold(
        appBar:AppBar(backgroundColor:Colors.blue,
                      leading:Icon(Icons.arrow_back),
                      title:Text("Roberto Carlos Chavez "),
                      actions: [
          Icon(Icons.search),

          Icon(Icons.more_vert)
        ],
        elevation: 8,

        ),
        body: Center(
          
          
        ),
      ),
    );
  }
}
