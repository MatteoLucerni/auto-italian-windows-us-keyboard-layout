## Custom “US-International No Dead Keys” Layout (Concise)

- **Base layout:** US-International  
- **Dead keys disabled:** `` ` ``, `~`, `'`, `"` and `^` send their symbol immediately  
- **Accented vowels:** AltGr (same of: Ctrl + Alt) + letter → correct italian accent; Shift+ AltGr → uppercase   
- **Caps = shift:** enabled on all accented-vowel entries -> Toggle Caps + AltGr → fixed uppercase  
- **No useless accents:** only correct accents for italian  

### Key mappings (AltGr / Shift+AltGr)

| Key | Output | Code point | Output | Code point |
|:---:|:------:|:----------:|:------:|:----------:|
| a   | à      | U+00E0     | À      | U+00C0     |
| e   | é      | U+00E9     | É      | U+00C9     |
| i   | ì      | U+00EC     | Ì      | U+00CC     |
| o   | ò      | U+00F2     | Ò      | U+00D2     |
| u   | ù      | U+00F9     | Ù      | U+00D9     |

### Example of usage

"Ctrl + Alt + e" -> é
"Ctrl + Alt + u" -> ù
"Shift + Ctrl + Alt + a" -> À
"Caps Lock" + "Ctrl + Alt + u" + "Ctrl + Alt + i" -> ÙÌ

### How to use it

1. Clone repo
2. Execute setup.exe
3. Restart pc
4. Open Settings -> Time & Language -> Language & region -> click on the three dots of you language and select "Language options"
5. Click on "Add a keyboard"
6. Select `US-International - No Dead Keys`
7. Remove other installed keyboards from the bottom page list

### Config file (optional)

`usi-ndk-layout.klc` is the config file that you can upload in Microsoft Keyboard Layout Creator (MSKLC) to personalize it or make your build for your system