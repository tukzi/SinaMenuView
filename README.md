SinaMenuView
====================

![License](https://img.shields.io/cocoapods/l/TWPhotoPicker.svg)
![Platform](https://img.shields.io/cocoapods/p/TWPhotoPicker.svg)

SinaMenuView is pop animation menu inspired by sina weibo app.

## Screenshots
![image](https://github.com/xhzengAIB/LearnEnglish/raw/master/Screenshots/XHSinaMenuViewExample.gif)

## Installation

With [CocoaPods](http://cocoapods.org/), add this line to your `Podfile`.

```
pod 'XHSinaMenuView'
```

and run `pod install`, then you're all done!

## How to use

```objc
NSMutableArray *items = [[NSMutableArray alloc] initWithCapacity:3];
MenuItem *menuItem = [[MenuItem alloc] initWithTitle:@"Flickr" iconName:@"post_type_bubble_flickr" glowColor:[UIColor grayColor] index:0];
[items addObject:menuItem];
    
menuItem = [[MenuItem alloc] initWithTitle:@"Googleplus" iconName:@"post_type_bubble_googleplus" glowColor:[UIColor colorWithRed:0.000 green:0.840 blue:0.000 alpha:1.000] index:0];
[items addObject:menuItem];
    
menuItem = [[MenuItem alloc] initWithTitle:@"Instagram" iconName:@"post_type_bubble_instagram" glowColor:[UIColor colorWithRed:0.687 green:0.000 blue:0.000 alpha:1.000] index:0];
[items addObject:menuItem];
    
menuItem = [[MenuItem alloc] initWithTitle:@"Twitter" iconName:@"post_type_bubble_twitter" glowColor:[UIColor colorWithRed:0.687 green:0.000 blue:0.000 alpha:1.000] index:0];
[items addObject:menuItem];
    
menuItem = [[MenuItem alloc] initWithTitle:@"Youtube" iconName:@"post_type_bubble_youtube" glowColor:[UIColor colorWithRed:0.687 green:0.000 blue:0.000 alpha:1.000] index:0];
[items addObject:menuItem];
    
menuItem = [[MenuItem alloc] initWithTitle:@"Facebook" iconName:@"post_type_bubble_facebook" glowColor:[UIColor colorWithRed:0.687 green:0.000 blue:0.000 alpha:1.000] index:0];
[items addObject:menuItem];
    
MenuView *centerButton = [[MenuView alloc] initWithFrame:self.view.bounds items:items];
[centerButton showMenuAtView:self.view];

```

## Requirements

* iOS 6.0+ 
* ARC

## License

English: SinaMenuView is available under the MIT license, see the LICENSE file for more information.     
