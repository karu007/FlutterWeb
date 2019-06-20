# FlutterWeb
![](https://i.ytimg.com/vi/uhSZEMV7l5E/maxresdefault.jpg)

This repository will guide you to give a headstart for flutter-web. Well, these steps are only for windows users.

# Here are the steps for those who already have flutter and getting crazy to start flutter-web:
0. Add flutter path into enironment variables
1. Make sure you have flutter path in environment variables. Verify this path by running `flutter --version` command in command prompt
- If you are on the right track output will kind of something this:
![](https://raw.githubusercontent.com/karu007/FlutterWeb/master/flutter_path_check.png)

- If you get something like below then do the step 0 properly:
![](https://raw.githubusercontent.com/karu007/FlutterWeb/master/flutter_path_check_error.png)

2. Run `flutter upgrade` on your windows command prompt with proper internet conencction.
3. Now once that command got finished, download this: [Dart SDK](http://www.gekorm.com/dart-windows/) depending on your windows platform.
4. Once downloaded install it in normal way you install any other windows software.
5. Set path of this dart SDK in environmental variables (...\Dart\dart-sdk\bin).
here is the glimpse of the process:
![](https://raw.githubusercontent.com/karu007/FlutterWeb/master/add_dart.png)
6. Verify that dart is added to your path by running `dart --verison` in your command prompt.
7. Once get it right, you will get to know something like this:
![](https://raw.githubusercontent.com/karu007/FlutterWeb/master/dart_path_check.png)
8. Now most important install [VSCode](https://code.visualstudio.com/download) editor because further steps are easier with this editor.
9. Once gets installed, welcome screen will show up but close it. And press `ctrl + shift + X` and type in the search box `flutter`, install this extension. Once gets installed it will look something like this.
![](https://raw.githubusercontent.com/karu007/FlutterWeb/master/flutter%20vscode.png)
10. One more extension we need so again press `ctrl + shift + X` and type in the search box `dart`, install this extension. Once gets installed it will look something like this.
![](https://raw.githubusercontent.com/karu007/FlutterWeb/master/dart_extension.png)
11. Wow! we are half way done. Congratulations!
12. Next first restart VSCode (reopen it after closing).
13. Press `ctrl + shift + P` type `flutterweb` and hit enter.
14. There might be a side dialog box appear for stagehand activation, allow it.
15. Enter project name where it asks for.
16. Choose project location.
16. Wait until index.html appeears
17. You may see an error in file called analysis_options.yaml, so just open that file and go to the link just above the include statement.
- It may look like this 
![](https://raw.githubusercontent.com/karu007/FlutterWeb/master/likn.png)
18. Copy the last include line of above image from that webpage and paste in place of already existed include statement, this will solve the problem.
- Once you done. Your file looks something like this:
![](https://raw.githubusercontent.com/karu007/FlutterWeb/master/final.png)
19. Now close this project in VSCode if the error was gone.
20. Well! now you have to open the same project folder in file explorer.
21. Go to your flutter directory where you have installed flutter looks like this:
![](https://raw.githubusercontent.com/karu007/FlutterWeb/master/files.png)
22. Now go to open .pub-cache/bin and copy the path and add this path to your environment variables where you have pasted the dart sdk or flutter path.
23. Open the command prompt in adminitrator mode and run the command `flutter pub global activate webdev`.
23. Once this done. Now run `flutter upgrade`.
24. Go to android studio, open that project, and click the Terminal from below options and type `flutter pub upgrade` something like this:
![](https://raw.githubusercontent.com/karu007/FlutterWeb/master/android.png)
...Wait for completion.
25. Wow! your'e done.
26. Just type `flutter pub global run webdev serve --auto restart` in the terminal of android studio as shown here:
![](https://raw.githubusercontent.com/karu007/FlutterWeb/master/last.png)
27. Now go to the link in the output i.e [http://127.0.0.1:8080](http://127.0.0.1:8080) mostly of this type.

