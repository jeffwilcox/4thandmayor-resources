# 4th and Mayor - Localization Project #

Hi, as many of us have spoken in the past, a key ask has been the availability of 4th & Mayor in many languages.

As hundreds of people have offered their support in localizing the app, I have finally started to take the time to prepare the underlying infrastructure here on GitHub to enable this.

The goal of this project is to support the languages that Foursquare also supports from a cloud-side; because many components - badges, messages, notes, notifications, warnings, etc. - are passed on from the cloud, this is a key limitation.

Thank you so much,
[http://twitter.com/jeffwilcox]("@jeffwilcox")

## Languages ##
The initial languages of interest (depending on developer interest) include:

- English (EN)
- Spanish (ES)
- French (FR)
- German (DE)
- Italian (IT)
- Japanese (JA)
- Russian (RU)
- Portuguese (PT)

Depending on interest level and community support are these additional languages, also supported by Foursquare:

- TH
- KO
- ID

You can see the supported language/country codes on this page on Foursquare: [https://developer.foursquare.com/overview/versioning](https://developer.foursquare.com/overview/versioning)

### Regional Languages ###
Regional languages are not necessarily supported on the server-side, but in situations where it makes sense for the client UI to be localized into variants, this is fine to do - with the understanding that server-provided content will still be in a more generic form that may or may not be appropriate for the sub-locale.

## Tools ##

- Windows 8 Operating System
- Visual Studio 2012 (Express or any SKU that can edit resource files, the format of the files is .resw)
- [Multilingual App Toolkit for Visual Studio 2012](http://msdn.microsoft.com/en-us/windows/apps/hh848309.aspx "Multilingual App Toolkit for Visual Studio 2012")

*The Multilingual Toolkit will work with VS2012 on Windows 7 in some situations I am told.*

## Process ##

Initially the process is designed for developers who are fluent in the language of interest. This is because the localization tools of choice include modern development environments at this time (Visual Studio or its localization tools, etc., plus a Windows 8 dependency) instead of a more traditional localization format such as Excel files that are shared.

The GitHub process, including fork and pull request, should be used.

Language translation should not be used if at all possible, unless to fill any last-minute strings before supporting a language; in such cases, issues should be opened relating to that language.

When submitting a pull request, the author should also make sure to update the CONTRIBUTORS.txt file with their desired display name under the language of contribution if they wish to be included in the app's credits.

## Thanks ##

Thank you, as always, for your efforts. It has been a long time coming :-)

## License ##

**This repo in GitHub and the content within it is under the Apache 2.0 license**. See also the LICENSE.txt file.

All contributions should adhere to the Apache 2.0 license as well; contributors understand that they are not receiving any special rights relating to compensation.

It is fine for other app developers, foursquare-apps, or not, to use these strings as they wish in their app, as long as they respect the 4th & Mayor trademark. 4th & Mayor(TM) is a trademark of Wilcox Digital, LLC.