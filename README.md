# Keyrune Icons Flutter

Lets you use Magic: The Gathering set symbols as icons in your flutter project! 

This is a package which wraps the symbol font [keyrune](https://github.com/andrewgioia/Keyrune) by Andrew Gioia, and allows it to be used as icons in flutter.

## Getting started

### Install

```yaml
dependencies:
  keyrune_icons_flutter: ^3.15.0
```

## Usage

```dart
// import the package
import 'package:keyrune_icons_flutter/keyrune_icons_flutter.dart';

// use the icons directly
const Icon(KeyruneIcons.ss_10e)

// use icons by string
const Icon(KeyruneIcons.icons["10e"])
```

Check out keyrune's [docs](https://keyrune.andrewgioia.com/icons.html) for available icons.


## License

All set symbol images are trademarks of Wizards of the Coast ([http://magicthegathering.com](https://magicthegathering.com)). This package is lisenced under GNU AGPL v3.0 or later. 

Please see keyrune's [LICENSE.md](https://github.com/andrewgioia/keyrune/blob/master/LICENSE.md) file for information about the keyrune icon font's license.
