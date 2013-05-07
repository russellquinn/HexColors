HexColors
=========

iOS SDK / Objective C

Adds basic support for hex colors to UIColor.


Usage:

1. Add the file to your project. Include UIColor+HexColors.h in your Prefix Header for Ultimate Good Timez.

2. To get a UIColor from a hex string, use: (without leading #)

	[UIColor colorFromHexString:@"ffffff"]; 

3. To get a hex string from a UIColor, use:

	[UIColor hexStringFromColor:[UIColor whiteColor]];