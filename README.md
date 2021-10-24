# bay8
24-10-210
import 'package:flutter/material.dart';

void main() => runApp(MyApp());


class MyApp extends StatelessWidget {
   @override
  state <StatelessWidget> createState(){
     return_MyAppState();
   }
}

class _MyAppState extends state<MyApp>{
  final questions= const [
    //1st
    {
      'questionText':'Q1. AMI abar BEYA JKORBO koba ?',
      'answer':[
        {'text':'aj','score':10},
        {'text':'kal','score':-2},
        {'text':'porsu','score':-2},
        {'text':'nextweek','score':-2}
      ]
    },
    {
      'questionText':'Q1. ami prem korbo koba?',
      'answer':[
        {'text':'aj','score':10},
        {'text':'kal','score':-2},
        {'text':'porsu','score':-2},
        {'text':'nextweek',score':-2},
      ]

    },
    {
      'questionText':'Q1. amar gf lagba akta koba haba?',
      'answer':[
        {'text':'aj','score':10},
        {'text':'kal','score':-2},
        {'text':'porsu','score':-2},
        {'text':'nextweek','score':-2},
      ]

    },
    {
      'questionText':'Q1. darling koba haba?',
      'answer':[
        {'text':'aj','score':10},
        {'text':'kal','score':-2},
        {'text':'porsu','score':-2},
        {'text':'nextweek','score':-2},
      ]

    },
  ];//end of questine object
var _quedtionIndext=0;
var _totalScore=0;

}

