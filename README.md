# pwa-memo

對遇到的問題做一些筆記  

## manifest
* 該網域不安全，但想測試的話，可以於 ```chrome://flags/#unsafely-treat-insecure-origin-as-secure``` 加入該網域


## service worker

## ios
* 目前不支援 beforeinstallprompt，參考: [這裡](https://developer.mozilla.org/en-US/docs/Web/API/BeforeInstallPromptEvent)
* 設定主畫面圖片、開啟程式顯示Logo等設定，參考: [這裡](https://developer.apple.com/library/archive/documentation/AppleApplications/Reference/SafariWebContent/ConfiguringWebApplications/ConfiguringWebApplications.html)
* 設定開啟程式顯示的Logo這個功能，需設置```<meta name="apple-mobile-web-app-capable" content="yes">``` 才能正常顯示

### apple-touch-startup-image
* apple-touch-startup-image 指定的圖片，必須完全符合裝置寬高才會顯示
* 參考代碼: https://medium.com/appscope/adding-custom-ios-splash-screens-to-your-progressive-web-app-41a9b18bdca3
* 參考裝置寬高表: https://kapeli.com/cheat_sheets/iOS_Design.docset/Contents/Resources/Documents/index

