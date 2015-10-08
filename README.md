# Android-WebViewTest
Small WebView test project, stuff to know:
1 The bacis: define webview in xml, findViewById, and then load url, use webclient to open it the in view  

2 Decide which website to open: myWebclient and override shouldAvroidUrlLoading  

3 History back: onKeyDown and override KeyEvent.KEYCODE_BACK  

4 Add javascript: add code in /assets folder (for android studio just create a new one), make a javascriptinterface class, and load the javascript in /assets folder  

