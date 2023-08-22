# Number Formatter
A number formatter i wrote meant to be used in incremental games.

Currently supports up to DD (1e+39)
Requires [BreakInfinity.cs](https://github.com/Razenpok/BreakInfinity.cs) to be used

## Avalible Number Types
BigDouble 
int
long
float
double

## Usage
There are 2 ways to use this formatter
> Formatter.Format(format?);
> (number).Format(format?);

## Adding custom formats
Use the **AddFormat()** Method to add your own custom format or override existing formats.
Parameter **formatName** is the name formatName you want when calling **Formatter.Format(format)**
Parameter **values** is the Format you want it to be mapped to.

## Contributing
Feel free to contribute to this repo or fork this repo.
