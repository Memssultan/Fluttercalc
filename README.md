# BUTTONS
## Creating Stateless Widget for buttons
``````
class MyButton extends StatelessWidget {
``````
## Declaring variables 
``````
final color;
final textColor;
final buttonText;
final buttontapped;
``````
`we declare the variables that we use in this code`
## Constructor
``````
MyButton({this.color, this.textColor, this.buttonText, this.buttontapped});
``````
`creating a construct`

# MAIN
## Importing
``````
 import 'package:flutter/material.dart';
 import 'buttons.dart';
 import 'package:math_expressions/math_expressions.dart';
 ``````
`
we importing all we we need
`
## MyApp
`The main entry point for the Flutter application. It creates and runs an instance of the MyApp widget.`
## HomePage
` A stateful widget representing the main page of the calculator app. It contains the user interface for the calculator.`
## _HomePageState
` The state class associated with HomePage. It holds the state variables userInput and answer, which represent the input expression and the calculated result, respectively.`
## buttons
 `A list of strings representing the buttons that the calculator will have. These strings include digits (0-9), operators (+, -, *, /), and special buttons (C for clear, +/- for negation, % for percentage, DEL for delete, and = for calculation).`