GUAAlertView
============

Custom alert view with gesture support and block-based API.

## Preview

![screenshots](https://raw.githubusercontent.com/onlymelon/GUAAlertView/master/GUAAlertView.gif)


## Usage

Wherever you want to use GUAAlertView, import the header file as follows:

``` objective-c
#import "GUAAlertView.h"
```

Sample:

``` objective-c
GUAAlertView *v = [GUAAlertView alertViewWithTitle:@"title"
                                           message:@"message"
                                       buttonTitle:@"buttonTitle"
                               buttonTouchedAction:^{
                                       NSLog(@"button touched");
                                   } dismissAction:^{
                                       NSLog(@"dismiss");
                                   }];

[v show];
```

## Contact

- onlymelon42@gmail.com
