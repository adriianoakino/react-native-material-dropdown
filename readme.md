[npm-badge]: https://img.shields.io/npm/v/react-native-material-dropdown.svg?colorB=ff6d00
[npm-url]: https://npmjs.com/package/react-native-material-dropdown
[license-badge]: https://img.shields.io/npm/l/react-native-material-dropdown.svg?colorB=448aff
[license-url]: https://raw.githubusercontent.com/n4kz/react-native-material-dropdown/master/license.txt
[codeclimate-badge]: https://img.shields.io/codeclimate/maintainability/n4kz/react-native-material-dropdown.svg
[codeclimate-url]: https://codeclimate.com/github/n4kz/react-native-material-dropdown
[example-url]: https://github.com/adriianoakino/react-native-material-dropdown/blob/master/example.gif
[textinput]: https://facebook.github.io/react-native/docs/textinput.html#props
[touchable]: https://facebook.github.io/react-native/docs/touchablewithoutfeedback.html#props
[textfield]: https://github.com/n4kz/react-native-material-textfield#properties

# react-native-material-dropdown

[![npm][npm-badge]][npm-url]
[![license][license-badge]][license-url]
[![codeclimate][codeclimate-badge]][codeclimate-url]

Material dropdown with consistent behaviour on iOS and Android

![example][example-url]
## Properties
criador https://github.com/n4kz/react-native-material-dropdown

## Features
Implantado icone para avisar que há mais itens, como no principal não havia essa possíbilidade, clonei e adicionei para usar em meu projeto.



 name              | description                                   | type     | default
:----------------- |:--------------------------------------------- | --------:|:------------------
 label             | Text field label text                         |   String | -
 error             | Text field error text                         |   String | -
 animationDuration | Text field animation duration in ms           |   Number | 225
 fontSize          | Text field font size                          |   Number | 16
 labelFontSize     | Text field label font size                    |   Number | 12
 baseColor         | Text field base color                         |   String | rgba(0, 0, 0, .38)
 textColor         | Text field text color                         |   String | rgba(0, 0, 0, .87)
 itemColor         | Dropdown item text color (inactive item)      |   String | rgba(0, 0, 0, .54)
 selectedItemColor | Dropdown item text color (active item)        |   String | rgba(0, 0, 0, .87)
 disabledItemColor | Dropdown item text color (disabled item)      |   String | rgba(0, 0, 0, .38)
 dropdownPosition  | Dropdown position (dynamic if undefined)      |   Number | -
 itemCount         | Dropdown visible item count                   |   Number | 4
 itemPadding       | Dropdown item vertical padding                |   Number | 8
 itemTextStyle     | Dropdown item text styles                     |   Object | -
 dropdownOffset    | Dropdown offset                               |   Object | { top: 32, left: 0 }
 dropdownMargins   | Dropdown margins                              |   Object | { min: 8, max: 16 }
 data              | Dropdown item data                            |    Array | []
 value             | Selected value                                |   String | -
 containerStyle    | Styles for container view                     |   Object | -
 overlayStyle      | Styles for overlay view                       |   Object | -
 pickerStyle       | Styles for item picker view                   |   Object | -
 shadeOpacity      | Shade opacity for dropdown items              |   Number | 0.12
 rippleOpacity     | Opacity for ripple effect                     |   Number | 0.54
 rippleInsets      | Insets for ripple on base component           |   Object | { top: 16, bottom: -8 }
 rippleCentered    | Ripple on base component should be centered   |  Boolean | false
 renderBase        | Render base component                         | Function | -
 renderAccessory   | Render text field accessory                   | Function | -
 valueExtractor    | Extract value from item (args: item, index)   | Function | ({ value }) => value
 labelExtractor    | Extract label from item (args: item, index)   | Function | ({ label }) => label
 propsExtractor    | Extract props from item (args: item, index)   | Function | () => null
 onChangeText      | Selection callback (args: value, index, data) | Function | -
 iconName          | Name icon - tutorial react native icon        | String   | chevron-down
 iconType          | Type icon - tutorial react native icon        | String   | entypo
 iconColor         | Color icon - tutorial react native icon       | String   | #000

Other [TextField][textfield], [TextInput][textinput] and [TouchableWithoutFeedback][touchable] properties will also work

## Methods

 name            | description                    | returns
:--------------- |:------------------------------ |:--------
 focus()         | Acquire focus (open dropdown)  | -
 blur()          | Release focus (close dropdown) | -
 value()         | Get current value              | String
 selectedIndex() | Get selected index             | Number
 selectedItem()  | Get selected item              | Object
 isFocused()     | Get current focus state        | Boolean

