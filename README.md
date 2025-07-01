## US Auto accents: Custom US Layout with auto correct accents for Italian

- **Base layout:** US
- **Dead keys disabled:** `` ` ``, `~`, `'`, `"` and `^` send their symbol immediately
- **Accented vowels:** "Ctrl + Shift + letter" → correct italian accent
- **No useless accents:** only correct accents for italian
- **No useless uppercase:** c'mon you know that uppercase accented letters are useless

### Key mappings (Ctrl + Shift + Alt + Key)

| Key | Output | Code point |
| :-: | :----: | :--------: |
|  a  |   à    |   U+00E0   |
|  e  |   è    |   U+00E8   |
|  i  |   ì    |   U+00EC   |
|  o  |   ò    |   U+00F2   |
|  u  |   ù    |   U+00F9   |

### Key mappings (Ctrl + Shift + Key)

| Key | Output | Code point |
| :-: | :----: | :--------: |
|  e  |   é    |   U+00E9   |

### Example of usage

"Ctrl + Shift + Alt + e" -> è
"Ctrl + Shift + Alt + u" -> ù
"Ctrl + Shift + e" -> é

### How to use it on your machine

1. Clone repo
2. Execute setup.exe
3. Restart pc
4. Open Settings -> Time & Language -> Language & region -> click on the three dots of you language and select "Language options"
5. Click on "Add a keyboard"
6. Select `US - Auto accents`
7. Remove other installed keyboards from the bottom page list

### Config file (optional)

`US-Auto Accents Config.klc` is the config file that you can upload in Microsoft Keyboard Layout Creator (MSKLC) to personalize it or make your build for your system
