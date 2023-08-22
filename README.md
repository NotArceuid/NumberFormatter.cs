# Number Formatter
A number formatter meant to be used in incremental games.

Currently supports up to DD (1e+39)
Requires [BreakInfinity.cs](https://github.com/Razenpok/BreakInfinity.cs) to be used

## Supported Numberic Types
- BigDouble 
- int
- long
- float
- double

### Usage
There are 2 ways to use this formatter
+ Formatter.Format(format?);
+ (number).Format(format?);

*format?* is the format type you want to use. Leave it blank if you want to use the default settings.

*Formatter* class also contains settings such as **FormatType** and **SignificantDigits**.

## Adding custom formats
You can use the **AddFormat()** Method to add your own custom format or override existing formats.

+ **formatName** is the name formatName you want when calling **Formatter.Format()**
+ **values** is the Format you want it to be mapped to.
