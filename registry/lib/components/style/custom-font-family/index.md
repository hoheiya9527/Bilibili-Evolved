使用组件提供的字体设置覆盖原版的主站字体，并使主站字体可被自定义。

当组件被启用后，几乎所有的元素会立即应用组件提供的字体设置。

选项说明:
- `禁用标题标点符号缩进`: 在新版视频页中，推荐视频栏中的视频标题，如果首个字符是特定的标点符号，则文本会缩入左侧。这个选项可以禁用这种样式
- `更多选项`:
  - `自定义字体`: 设置自定义字体。写法请参考 [MDN](https://developer.mozilla.org/zh-CN/docs/Web/CSS/font-family)、默认设置与设置说明。
  - `覆盖选项`: 相当于一个白名单，使用了特殊字体的元素会被加入其中。默认情况下这些元素不会应用组件提供的字体设置，只有在启用对应的选项后才会应用。