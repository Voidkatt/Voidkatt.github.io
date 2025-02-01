import 'package:flutter/material.dart';

void main() {
  runApp(MyApp());
}

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Calculator(),
    );
  }
}

class Calculator extends StatefulWidget {
  @override
  _CalculatorState createState() => _CalculatorState();
}

class _CalculatorState extends State<Calculator> {
  String _output = "0";
  String _currentOperation;
  double _firstNumber;
  double _secondNumber;

  void _buttonPressed(String buttonText) {
    setState(() {
      if (buttonText == "C") {
        _output = "0";
        _currentOperation = null;
        _firstNumber = 0;
        _secondNumber = 0;
      } else if (buttonText == "+" || buttonText == "-" || buttonText == "*" || buttonText == "/") {
        _firstNumber = double.parse(_output);
        _currentOperation = buttonText;
        _output = "0";
      } else if (buttonText == ".") {
        if (!_output.contains(".")) {
          _output += buttonText;
        }
      } else if (buttonText == "=") {
        _secondNumber = double.parse(_output);

        switch (_currentOperation) {
          case "+":
            _output = (_firstNumber + _secondNumber).toString();
            break;
          case "-":
            _output = (_firstNumber - _secondNumber).toString();
            break;
          case "*":
            _output = (_firstNumber * _secondNumber).toString();
            break;
          case "/":
            _output = (_firstNumber / _secondNumber).toString();
            break;
        }

        _currentOperation = null;
        _firstNumber = 0;
        _secondNumber = 0;
      } else {
        if (_output == "0") {
          _output = buttonText;
        } else {
          _output += buttonText;
        }
      }
    });
  }

  Widget _buildButton(String buttonText) {
    return Expanded(
      child: OutlinedButton(
        onPressed: () => _buttonPressed(buttonText),
        child: Text(
          buttonText,
          style: TextStyle(
            fontSize: 20.0,
          ),
        ),
      ),
    );
  }

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(title: Text('Calculadora Básica')),
      body: Column(
        children: <Widget>[
          Container(
            alignment: Alignment.centerRight,
            padding: EdgeInsets.symmetric(vertical: 24.0, horizontal: 12.0),
            child: Text(
              _output,
              style: TextStyle(fontSize: 48.0),
            ),
          ),
          Expanded(
            child: Divider(),
          ),
          Column(children: [
            Row(children: [
              _buildButton("7"),
              _buildButton("8"),
              _buildButton("9"),
              _buildButton("/")
            ]),
            Row(children: [
              _buildButton("4"),
              _buildButton("5"),
              _buildButton("6"),
              _buildButton("*")
            ]),
            Row(children: [
              _buildButton("1"),
              _buildButton("2"),
              _buildButton("3"),
              _buildButton("-")
            ]),
            Row(children: [
              _buildButton("."),
              _buildButton("0"),
              _buildButton("00"),
              _buildButton("+")
            ]),
            Row(children: [
              _buildButton("C"),
              _buildButton("=")
            ])
          ])
        ],
      ),
    );
  }
}
