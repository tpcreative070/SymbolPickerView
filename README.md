# SymbolPicker

`SymbolPickerView` is a Swift Package that provides a customizable UI component for browsing and selecting [Apple's SF Symbols](https://developer.apple.com/sf-symbols/). This package includes access to symbol metadata and offers flexible presentation options for symbol pickers.

## 📦 Installation

You can add `SymbolPickerView` to your project using [Swift Package Manager](https://swift.org/package-manager/).

### In Xcode:

1. Open your project.
2. Go to **File > Add Packages…**
3. Enter the package URL:
   ```
   https://github.com/tpcreative070/SymbolPickerView
   ```
4. Select the version range you want to use (recommend "Up to Next Major").
5. Import `SymbolPickerView` in the files where you need it:
   ```swift
   import SymbolPickerView
   ```
6. Each presenting view must instantiate an instance of the SymbolLoader class as a @State property or be able to fetch it from the Environment as this is passed on to the SymbolView when being presented.

   ```swift
   @State private var loader = SymbolLoader()
   ```
