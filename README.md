# btt_reset_trial
Reset trial time for Better Touch Tool


`kill $(ps aux | grep 'BetterTouchTool' | awk '{print $2}')`

`rm -rf ~/Library/Preferences/com.hegenberg.BetterTouchTool.plist`

`rm -rf ~/Library/Application\ Support/BetterTouchTool/`

`rm -rf /Applications/BetterTouchTool.app`

And now you can install it again!  
`brew install --cask bettertouchtool`
