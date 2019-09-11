# brand_colors

This is just a collection of Color constants of the most popular brands and companies out there -- so you no longer have to keep Google-searching the hex codes for each.

## List of Colors

Conveniently browse through all the currently available colors through this [website](https://oliatienza.github.io/works/brand_colors.html#/)

## Usage

### Example
```
import 'package:brand_colors/brand_colors.dart';
import 'package:flutter/material.dart';

class Example extends StatelessWidget {
  const Example({Key key}) : super(key: key);

  @override
  Widget build(BuildContext context) {
    return Container(
      color: BrandColors.facebookBlue,
    );
  }
}
```