<div align="center">
  <h1>Sofle RGB Wireless Mechanical Keyboard</h1>
  <h5>ZMK Config for Sofle RGB</h5>
</div>

## Parts list

- [Sofle RGB](https://github.com/josefadamcik/SofleKeyboard)
- 2 x [nice!nano microcontrollers](https://nicekeyboards.com/nice-nano/)
- 2 x LiPo 2000mAh 401230 JST Batteries

## It adds the following features and fixes:

- Fixes split side encoder not working ([PR #728](https://github.com/zmkfirmware/zmk/pull/728))
- Adds automatic disabling and enabling of external power when USB is disconnected or connected ([PR #1184](https://github.com/zmkfirmware/zmk/pull/1184))
- Adds automatic disabling of backlight if the keyboard is idle ([PR #1179](https://github.com/zmkfirmware/zmk/pull/1179))
- Adds status lighting for layers/bluetooth profile/capsword/battery. ([PR #1475](https://github.com/zmkfirmware/zmk/pull/1475))
- Adds support for mouse movement/scrolling ([FTC](https://github.com/ftc/zmk))

Most of these fixes and features have not made it into the official zmk yet, because they don't meet the (very resaonable and completely understandable) code standards of the zmk maintainers.

However, while these fixes and features may not meet the quality standards of the official project, they work well enough to be used until these features get properly implemented in the official zmk.

## License

[MIT](https://choosealicense.com/licenses/mit/)
