# Codeforces Android App

## Development

A native Android app using Java for writing code.

### Installing

- Fork the repository. 
- Clone the repo using the terminal command. Make sure you replace `username` with your GitHub username.
```bash
git clone https://github.com/username/CodeforcesApp.git 
```

### Setting up the Android Project

1. Download the CodeforcesApp project source. You can do this either by forking and cloning the repository (recommended if you plan on pushing changes) or by downloading it as a ZIP file and extracting it.

2. Open Android Studio, you will see a Welcome to Android window. Under Quick Start, select _Import Project (Eclipse ADT, Gradle, etc.)_

3. Navigate to the directory where you saved the CodeforcesApp project, select the root folder of the project (the folder named "CodeforcesApp"), and hit OK. Android Studio should now begin building the project with Gradle.

4. Once this process is complete and Android Studio opens, check the Console for any build errors.

  - _Note:_ If you receive a Gradle sync error titled, "failed to find ...", you should click on the link below the error message (if available) that says _Install missing platform(s) and sync project_ and allow Android studio to fetch you what is missing.

5. Once all build errors have been resolved, you should be all set to build the app and test it.

6. To Build the app, go to _Build>Make Project_ (or alternatively press the Make Project icon in the toolbar).

7. If the app was built successfully, you can test it by running it on either a real device or an emulated one by going to _Run>Run 'app'_ or pressing the Run icon in the toolbar.


### Libraries used and their documentation

- Retrofit [Docs](http://square.github.io/retrofit/2.x/retrofit/)
- Butter Knife [Docs](https://github.com/JakeWharton/butterknife/)
- GSON Converter [Docs](https://github.com/square/retrofit/tree/master/retrofit-converters/gson/)
- Glide [Docs](https://github.com/bumptech/glide)
- Recycler View Animators [Docs](https://github.com/wasabeef/recyclerview-animators)
- Custom Tabs [Docs](https://developer.android.com/reference/android/support/customtabs/package-summary)

### API Used

Codeforces API [Docs](https://codeforces.com/api/help)

## Built With

- Android Studio

## License

This project is licensed under the Apache License.
