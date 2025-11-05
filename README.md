The Java Math Class: A Brief Introduction

java.lang.Math is a built-in class in the Java programming language. It provides many essential methods and two constants required for various mathematical calculations.

Key Features:

No Import Needed: This class is part of the java.lang package, so you do not need to import it separately. Java loads it automatically.

Everything is Static: All methods and constants in this class are static. This means you do not need to create an object of the Math class to use it. You can call the methods directly using the class name.

Example: double result = Math.pow(2, 3); // Result is 8.0

Important Constants:

Math.PI: The value of Pi ($\pi$) (approximately 3.14159...).

Math.E: The value of Euler's number ($e$) (approximately 2.71828...).

Some Commonly Used Methods:

Math.pow(double a, double b): Calculates $a$ raised to the power of $b$ ($a^b$).

Math.sqrt(double a): Calculates the square root of $a$ ($\sqrt{a}$).

Math.max(double a, double b): Returns the larger of the two numbers.

Math.min(double a, double b): Returns the smaller of the two numbers.

Math.abs(double a): Returns the absolute value of a number (e.g., Math.abs(-5) returns 5).

Math.random(): Returns a random double value in the range [0.0, 1.0) (0.0 is inclusive, 1.0 is exclusive).

Math.round(double a): Rounds a decimal number to the nearest whole number (as a long).

Math.ceil(double a): Rounds a decimal number up to the nearest integer (returns a double, e.g., Math.ceil(7.2) returns 8.0).

Math.floor(double a): Rounds a decimal number down to the nearest integer (returns a double, e.g., Math.floor(7.8) returns 7.0).

Trigonometry Methods:

Math.sin(double a)

Math.cos(double a)

Math.tan(double a)

Important: These trigonometric methods accept the angle in radians. If you have an angle in degrees, you must first convert it to radians using the Math.toRadians(double deg) method.
