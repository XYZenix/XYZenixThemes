## Contributing
if you want to contribute, you can open pull requests i guess

most themes use scss, compiled using [dart-sass](https://sass-lang.com/dart-sass/)
so if you're going to open a pull request modifying those themes, either don't provide a modified .css file, or use dart-sass with the default settings so the output is the same and doesn't end up changing 500 other unrelated things due to slight formatting differences

if there is no scss file, it's safe to assume there was no scss used so just modify the css file itself