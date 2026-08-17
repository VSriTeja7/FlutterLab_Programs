import 'package:flutter/material.dart';

void main() {
  runApp(
    MaterialApp(
      debugShowCheckedModeBanner: false,
      title: "Student Profile Card",
      home: Scaffold(
        backgroundColor: Colors.blueGrey[50],
        appBar: AppBar(
          backgroundColor: Colors.blue,
          centerTitle: true,
          title: Text(
            "Student Profile Card",
            style: TextStyle(fontSize: 25, fontWeight: FontWeight.bold),
          ),
        ),
        body: Center(
          child: Container(
            width: 320,
            padding: EdgeInsets.all(20),
            decoration: BoxDecoration(
              color: Color(0xff9ef9ff),
              borderRadius: BorderRadius.circular(15),
              boxShadow: [
                BoxShadow(color: Colors.grey, blurRadius: 5),
              ],
            ),
            child: Column(
              mainAxisSize: MainAxisSize.min,
              children: [
                CircleAvatar(
                  radius: 45,
                  backgroundImage: NetworkImage(
                    "data:image/jpeg;base64,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",
                  ),
                ),
                SizedBox(height: 20),
                Text(
                  "V.Sri Teja",
                  style: TextStyle(
                    fontSize: 22,
                    fontWeight: FontWeight.bold,
                  ),
                ),
                SizedBox(height: 8),
                Text(
                  "Roll Number: 24PA1A05N4",
                  style: TextStyle(fontSize: 16),
                ),
                SizedBox(height: 5),
                Text(
                  "Branch: CSE",
                  style: TextStyle(fontSize: 16),
                ),
                SizedBox(height: 20),
                Container(
                  padding: EdgeInsets.all(10),
                  decoration: BoxDecoration(
                    color: Colors.white,
                    borderRadius: BorderRadius.circular(10),
                    boxShadow: [
                      BoxShadow(color: Colors.grey, blurRadius: 3),
                    ],
                  ),
                  child: Row(
                    mainAxisSize: MainAxisSize.min,
                    children: [
                      Icon(Icons.phone),
                      SizedBox(width: 10),
                      Text("807412900"),
                    ],
                  ),
                ),
                Container(
                  margin: EdgeInsets.all(8),
                  padding: EdgeInsets.all(10),
                  decoration: BoxDecoration(
                    color: Color(0xffebffec),
                    borderRadius: BorderRadius.circular(10),
                    boxShadow: [
                      BoxShadow(color: Colors.grey, blurRadius: 3),
                    ],
                  ),
                  child: Row(
                    mainAxisSize: MainAxisSize.min,
                    children: [
                      Icon(Icons.email),
                      SizedBox(width: 10),
                      Text("sri@example.com"),
                    ],
                  ),
                ),
              ],
            ),
          ),
        ),
      ),
    ),
  );
}
