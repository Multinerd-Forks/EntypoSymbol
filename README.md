#### EntypoSymbol ![CocoaPods Version](https://img.shields.io/cocoapods/v/EntypoSymbol.svg?style=flat) ![Platform](https://img.shields.io/cocoapods/p/EntypoSymbol.svg?style=flat) ![License](https://img.shields.io/cocoapods/l/EntypoSymbol.svg?style=flat)

- Icon font library for Swift. Currently supports Entypo. ObjectiveC version is [here](https://github.com/tichise/EntypoSymbolObjC).
- Entypoアイコンをシンボルフォントで呼び出せるライブラリです。ObjecitveC版は[こちら](https://github.com/tichise/EntypoSymbolObjC).
 - 詳細な使い方は[qiita](http://qiita.com/tichise/items/0b26a7a47c3862c4ca50)に記載してます。

#### Image
<img src="https://s3.amazonaws.com/cocoacontrols_production/uploads/control_image/image/6387/_____.png" width="160px">

#### Licence
font used in this project

Author of the font used in this  project: Entypo
Link: http://www.entypo.com/

Creative Commons Attribution 4.0 International (CC BY 4.0)

#### Examples Swift

##### Image

```html
import EntypoSymbol

var symbol:EntypoSymbol = EntypoSymbol(text:EntypoIcon.install, size:25)
symbol.addAttribute(NSForegroundColorAttributeName, value: UIColor.redColor())
var iconImage:UIImage = symbol.imageWithSize(CGSizeMake(25, 25))
```

```html
import EntypoSymbol

sampleLabel.font = EntypoFont.fontOfSize(40)
sampleLabel.text = EntypoIcon.creativeCommons
```


#### Examples Objective C

##### Image

```html
@import EntypoSymbol;

EntypoSymbol *symbol = [[EntypoSymbol alloc] initWithText:[EntypoIcon install] size:30];
[symbol addAttributeWithAttributeName:NSForegroundColorAttributeName value:[UIColor blackColor]];
sampleImageView.image = [symbol imageWithSize:CGSizeMake(30, 30)];
```

```html
@import EntypoSymbol;

sampleLabel.font = [EntypoFont fontOfSize:20];
sampleLabel.text = [EntypoIcon install];
```

#### Installation (CocoaPods)
` pod EntypoSymbol `