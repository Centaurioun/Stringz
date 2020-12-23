<p align="center">
<img src="https://raw.githubusercontent.com/mohakapt/Stringz/master/app_icon.png">
</p>

<p align="center"><i>It is Strings but with a Z 😬</i></p>

![Stingz](https://raw.githubusercontent.com/mohakapt/Stringz/master/hero_image.png)
<p align="center"><i>Loved the project? Please share it with your friends and give it a ⭐️</i></p>

> Stringz is a lightweight yet powerful editor that makes translating your iOS app easy and fast.

<h2 id='section_description'>
✏️ Description
</h2>

Stringz greatly simplifies localizing your Xcode apps (iOS, macOS, tvOS and watchOS) by introducing a powerful editor for all localizable files in your project.
It will even import strings from storyboard and xib files saving you a lot of time and effort finding elementIds in the storyboard.
Stringz also supports localizing your Info.plist file so you can easily translate your app name and permission descriptions.

Stringz will also highlight missing translations and warn you about duplicate values and has many more useful features that takes a painful and tedious task like localizing your app and converts it to an easy and simple task.

<h2 id='section_features'>
✨ Features
</h2>

* ✅ Automatically finds localizable files in an Xcode project.
* ✅ Displays translations in a table side by side and highlights missing values.
* ✅ Supports all kinds of localizable files like .strings, .storyboard, .xib and .plist.
* ✅ Supports adding new languages and localizing unlocalized files.
* ✅ Easy to use and mac in it's core.
* ✅ Continuously being improved and updated.


<h2 id='section_table_of_contents'>
🚧 Table of Contents
</h2>

- [🚀 Motivation](#section_motivation)
- [⬇️ Installation](#section_installation)
- [🔌 Usage](#section_usage)
- [🤝 Contributing](#section_contributing)
- [💡 FAQ](#section_faq)
- [⚒️ Dependencies](#section_dependencies)
- [👍 Support](#section_support)
- [📝 License](#section_license)


<h2 id='section_motivation'>
🚀 Motivation
</h2>


<h2 id='section_installation'>
⬇️ Installation
</h2>

1. Go to [releases](https://github.com/mohakapt/Stringz/releases) page for this repository.
1. Download the latest version of the app from the assets section. (It should be named something like Stringz-x.x.x.dmg).
1. Open the downloaded file and drag the app to your Applications folder.
1. The application doesn't have auto update feature (yet), so make sure to occasionally check this github repository for new releases.

<h2 id='section_usage'>
🔌 Usage
</h2>

Open the application and select your Xcode project (.xcodeproj) in the open dialog, Stringz will then automatically crawl your project, find localizable files, and diplay them in the sidebar. Select a localizable file from the sidebar to view its contents. From there you can add/delete/update strings and add new languages.

The application has autosave feature so it should automatically save your changes as you make them (You can also disable this feature from preferences if you don't want Xcode to reload every time you update a string).

Preferences also contains some useful options regarding loading localizable files and exporting .strings files to your project. So I would storngly advice to to check preferences out.

There is a sample app included in this repository, The application was tested havily with this sample app, So I strongly encorage you to download the sample app and run Stringz on it to examin how Stringz should correctly work, If you encounter an unexpected behaviors with your own app please consider submitting an [issue](https://github.com/mohakapt/Stringz/issues) and I'l make sure to fix it as quickly as possible.

<h2 id='section_contributing'>
🤝 Contributing
</h2>

This project is not open soruce, but that doesn't mean you can't contribute to the development of the project. A great way to help pushing this project forward is to download it and test it on your applications then submit an [issue](https://github.com/mohakapt/Stringz/issues) about any bugs, crashes or any unexpected behaviors you might encounter, Also suggestions and feature requests are super welcomed. So if you encounter some kind of inconvenience please don't give up on the application, submit an [issue](https://github.com/mohakapt/Stringz/issues) and help make this project better.

<h2 id='section_faq'>
💡 FAQ
</h2>


<h2 id='section_dependencies'>
⚒️ Dependencies
</h2>

Stringz uses `XcodeEditor` to open xcode projects and browse their contents


<h2 id='section_support'>
👍 Support
</h2>


<h2 id='section_license'>
📝 License
</h2>
<!--
## Installation
1. Clone this repository somewhere on your mac.
2. Run the following command in Terminal:

```ruby
pod install
```

3. Open `Stringz.xcworkspace`, Build the project and run it on your mac.
4. That's it.

## Requirements
* Runtime: macOS 10.12 or greater (Yeah! I know, I'll try to pull this down very soon)
* Build: Xcode 8 and 10.12 SDK or greater

## Stuff i'd love to implement -as soon as i get some free time-
* Code spider to analyze the code and extract strings from classes
* Fetch initial translation from Google Translate
* Support for storyboards and xibs
* Support for Android strings
* Ability to enable internationalization on project
* Recent search history
* Support for untranslatable strings
* Ability to catigorize strings in the .strings file

## Dependencies


## Important
Stringz still in its **beta versions**. Your app is amazing and i don't want it to get ruined because of me, so please do what any cautious developer would do and make a commit before using Stringz or (if you don't have version control in your app) make a backup of your app.

## Contributions
Stringz is my first macOS project so if you run into some messy code please don't judge instead create a pull request into `development` branch and i will be more than happy to merge it (Explaining what you changed and why would be highly appreciated).

## License
Stringz is available under the MIT license. See the LICENSE file for more information. -->
