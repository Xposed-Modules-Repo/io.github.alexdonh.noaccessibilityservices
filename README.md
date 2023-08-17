# no-accessibility-services

An Xposed module that disables apps from getting installed and enabled accessibility services.

## Purpose

Out of the blue, many banking and wallet apps in my country started forcing users to disable Accessiblity Services for all apps using it for security's sake (!?). So if you're using some Launcher that makes use of Accessibility to turn of screen with a gesture, you're fucked. If you're using some kind of tools to control your devices from PC (e.g. Samsung Link to Windows), you're fucked. If you're using Button Mapper to customize your hardware buttons, you're also fucked.

Or you can get your devices rooted, Xposed, load this module and fuck them back.

## Usage

- Install 
- Activate
- Select apps (System Framework may need to be selected too)
- (Force stop those apps)
- Enjoy!

It's only been tested on LSPosed (v1.8.6 - Zygisk). Refer to [Supported Hook Framework](https://fankes.github.io/YukiHookAPI/en/guide/home.html#suppored-hook-framework) to see if it works on your end.

## Credits

- [LSPosed](https://github.com/LSPosed)
- [YukiHookAPI](https://github.com/fankes/YukiHookAPI)

## License

MIT License

Copyright (c) 2023 Alex Do

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
