# suc_translating_highlighted_text_with_ollama_model
free program for translating highlighted text with ollama model

It works with any text that is highlighted in a browser, PDF reader, or text file.


add script on home om ubuntu 24


chmod +x ~/ollama_translate.sh

افتح Settings (الإعدادات) في أوبنتو.

اذهب إلى Keyboard -> Keyboard Shortcuts -> View and Customise Shortcuts.

انزل للأسفل واختر Custom Shortcuts.

اضغط على علامة (+) لإضافة اختصار جديد:

    Name: Ollama Translate

    Command: اكتب المسار الكامل للملف (استبدل username باسم مستخدم جهازك):
    /home/username/ollama_translate.sh

    Shortcut


sudo apt update

sudo apt install curl jq wl-clipboard zenity

sudo apt install jq



Switching languages: If you ever need to translate from Arabic to English, you can simply create a second script file and change the phrase "Translate to Arabic" to "Translate to English."

Updating models: Since the world of artificial intelligence is constantly evolving, you can always load newer models using `ollam` and change their name on the first line of the script.

Shortcuts: Make sure you memorize your keyboard shortcuts; they will save you hours of copying and pasting in browsers.
