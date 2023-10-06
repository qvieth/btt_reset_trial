# btt_reset_trial
Reset trial time for Better Touch Tool

Remember to save your preset  

<img src='image.png'>


```sh
echo "remove ~/Library/Application\ Support/BetterTouchTool/"
rm -rf ~/Library/Application\ Support/BetterTouchTool/
echo "Done"

echo "remove /Applications/BetterTouchTool.app"
rm -rf /Applications/BetterTouchTool.app
echo "Done"

echo "kill BetterTouchTool"
kill $(ps aux | grep 'BetterTouchTool' | awk '{print $2}')
echo "Done"

echo "uninstall BetterTouchTool"
brew uninstall --cask bettertouchtool
echo "Done"

echo "install BetterTouchTool"
brew install --cask bettertouchtool
echo "Done"
```
