# btt_reset_trial
Reset trial time for Better Touch Tool

Remember to save your preset  

<img src='image.png'>


```sh
kill $(ps aux | grep 'BetterTouchTool' | awk '{print $2}')
rm -rf ~/Library/Preferences/com.hegenberg.BetterTouchTool.plist
rm -rf ~/Library/Application\ Support/BetterTouchTool/
rm -rf /Applications/BetterTouchTool.app
brew install --cask bettertouchtool`
```
