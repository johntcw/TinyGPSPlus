This is a clone to Arduiniana's TinyGPSPlus library.

Changed the original functions:

double TinyGPSLocation::lat()
double TinyGPSLocation::lng()

To:
String TinyGPSLocation::lat()
String TinyGPSLocation::lng()

for more precise location.
