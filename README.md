# Stock Analyzer (C# / WinForms)

A C# Windows Forms application developed to analyze historical stock data and
identify common technical candlestick patterns as part of a personal learning
project.

## Features
- Identifies common candlestick patterns, including:
  - Doji
  - Hammer
  - Inverted Hammer
  - Marubozu
  - Engulfing
  - Harami
- Uses a simple, modular recognizer structure for pattern detection
- Basic graphical interface for displaying stock data and analysis results
- Clear separation between pattern logic and UI code

## Technologies
- C#
- .NET Framework 4.8
- Windows Forms

## Project Structure
MyStockAnalyzer/
├── CandlestickBuilder.cs
├── SmartCandlesticks.cs
├── Recognizer.cs
├── Recognizer_Doji.cs
├── Recognizer_Hammer.cs
├── Recognizer_InvertedHammer.cs
├── Recognizer_Marubozu.cs
├── Recognizer_EngulfingPattern.cs
├── Recognizer_HaramiPattern.cs
├── Form_Home.cs
├── Form_Display.cs
└── Program.cs

## Overview
This project was created to practice object-oriented programming concepts in C#.
Each candlestick pattern is implemented as a separate recognizer class, making
the code easier to understand and extend while learning design fundamentals.

## What I Learned
- Basic object-oriented programming principles in C#
- Implementing pattern detection logic
- Working with time-series financial data
- Building desktop applications using Windows Forms

## How to Run
1. Open `MyStockAnalyzer.sln` in Visual Studio
2. Build and run the project
3. Load sample stock data to view detected patterns

## Possible Improvements
- Add support for more candlestick patterns
- Improve UI layout and usability
- Add basic unit tests
- Refactor code for improved readability
