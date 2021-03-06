# Weather Plus #

* Author: Adriano Barbieri
* NVDA compatibility: 2017.3 to 2019.3
* Download: [Stable Version][1]

# ABOUT WEATHER PLUS: #

* This plugin adds local temperature and forecasts to 24 hours up to 9 additional days for NVDA.
* Copyright (C) [Adriano Barbieri](mailto:adrianobarb@yahoo.it)
* Released under the GNU GPL (General Public License) v2
* Weather Plus works through the use and presence of the following services:
* [https://developer.yahoo.com/weather/](https://developer.yahoo.com/weather/)
* [http://woeid.rosselliot.co.nz/lookup/](http://woeid.rosselliot.co.nz/lookup/)
* [http://www.geonames.org/](http://www.geonames.org/)
* [http://veloroutes.org/elevation/](http://veloroutes.org/elevation/)
* [http://www.nvda.it/](http://www.nvda.it/)

# USAGE: #

* Press NVDA+w to get the information about current temperature and weather conditions.
* Press NVDA+shift+W to get 24 hours forecast and forecast up to 9 days.
* Press NVDA+shift+control+w to set a temporary city.
* Press NVDA+shift+control+alt+w to open the Weather Plus settings dialog.
* Press NVDA+alt+w to get the date and time, when the weather report was updated.
* Press control+shift+w to toggle between Fahrenheit, Celsius or Kelvin temperature scales.

# Weather Plus setup: #

* You must set the Weather Plus addon before its first use! Go to the Preferences submenu, Weather Plus Settings submenu and choose one of the following options:
 * Set and Manage Your Cities... - Displays or allows to set the current city from a list.
 * Documentation - Opens the help file for the current language.
 * Check for Update... - Notifies about the availability of the new version.

To add a new city: press the following item:

* Set and Manage Your Cities... - Displays or allows to set the current city from a list.
* The following message is displayed only for the first time! Settings Preset None F1: help placing, F2: last TAB selection, F3: list and edit box, F4: control duration Weather Forecast, F5: volume controls.
* In the edit box, enter a City, woeID or choose one from the list, if available. Note: The F5 key is available if the sound effects are activated.
* After pressing enter on the item "Set and Manage Your Cities...", you will find other buttons as follows:
* Test - Testing the validity of woeID entry and find the name of city assigned or vice versa.
* Add - Adds the current city into your list. This button can be activated if you select a city from the list, when the city entered passed the test.
* Details - Displays information about the current city. This button is activated if you select a city from the list, or it has passed the test.
* Define - Allows you to define the area, in order to adapt the sound effects. This button can be activated if the audio effects are installed and activated, and you select a city from the list.
* Preset - Presets a city as the default, will be used every time you restart the plugin. This button is activated if you select a city previously inserted in the list and not preset, or it has passed the test.
* Remove - Deletes the current city from your list. This button can be activated if you select a city previously inserted in the list.
* Rename - Rename the current city. This button can be activated if you select a city previously inserted in the list.
* Import new cities... - This button allows you to import cities from the another list of cities with the extension *.zipcodes; you can select the city you want to import, by turning on the checkbox associated with it.
* Export your cities... - It allows you to save the cities in the specified file with the extension *.zipcodes. This button is activated if you have added and saved at least one city into the list.
* Scale of temperature measurement: Use the radio button to select between Celsius (by default), Fahrenheit and Kelvin.
* Degrees shown as: Use the radio button to select between: Celsius `-` Fahrenheit `-` Kelvin (by default) C `-` F `-` K or Unspecified.
* Combo box: Weather Forecasts up to days: 3; you can choose between 1 to 10 (3 days by default)
* To perform the following actions, toggle the following checkboxes:
* Copy the weather report and weather forecast, including city details to clipboard; checkbox not checked (by default)
* Enable audio effects (only for the current weather conditions); this checkbox also allows you to manage the installation of sound effects; if the sound effects are installed and the checkbox is activated, the F5 key and the volume setting becomes available.
* There will also be available an additional checkbox: "Use only weather effects".
* You can change the overall volume or change the last heard sound effect and filter out the others sounds in your environment. Checkbox is not checked by default.
* Use only weather effects - This option is available if sound effects are enabled; if is enabled, allows to listen only weather effects such as rain, wind, thunder, etc., filtering out all environmental ones. (unchecked by default)
* Enable the reading of the hours in 24-hour format. - If this checkbox is unchecked, announces the time in 12-hour format for example, 12 AM `-` 12 PM. Checkbox is checked (by default)
* Enable help buttons in the settings window; checkbox checked (by default)
* Read wind information; checkbox not checked (by default). If this checkbox is enabled, you can also activate the following checkboxes:
* Add wind direction; indicates the provenance of the wind. Checkbox checked (by default)
* Add speed of the wind; indicates the speed in kilometers or miles per hour. Checkbox checked (by default)
* Add speed in meters per second of the wind; checkbox checked (by default)
* Add perceived temperature; checkbox checked (by default)
* Read atmospherical information; checkbox not checked (by default). If enabled, you can also check the following checkboxes:
* Add humidity value; indicates the humidity in percent. Checkbox checked (by default)
* Add visibility value; indicate in kilometres or miles the distance visible. Checkbox checked (by default)
* Add atmospheric pressure value; indicates the atmospheric pressure in millibars or inches of mercury. If it's checked, enable an additional checkbox that allows you to indicate the pressure in millimeters of mercury. Checkbox checked (by default)
* Add status of barometric pressure; check box checked (by default)
* Read astronomical information; indicates the time of sunrise and sunset. Checkbox not checked (by default)
* Use the comma to separate decimals; if enabled, uses the comma as a decimal separator, otherwise, use the point. Checkbox not checked (by default)
* Check for upgrade; if is activated this alerts when there is an update of the addon. Checkbox checked (by default)
* Press the OK button to confirm the action or the Cancel button to cancel the action.
* If you have modified the cities list, by pressing "Cancel", you will be remembered and you can still save it. Note: your settings will be save in the file named:
* "Weather.ini": startup settings of Weather Plus.
* "Weather.volumes": custom audio volume levels, regardless of the overall volume.
* "Weather.zipcodes": list of cities with their zip code and definitions.
* "Weather_searchkey": search key saved.

--------------------------------------------------------------------------------

# What's new: #

# Version 7.4 #

* Fixed a bug in a city search function.

# Version 7.3 #

* Fixed unexpected bug in case of page not found while searching for updates.

# Version 7.2 #

* Fixed bug after adding a city, if it is the first one entered if you press ok button and restart the add-on.
* Now the progress dialog show again the time remaining and time elapsed.
* Correct Italian translation in the help of the Rename button.

# Version 7.1 #

* Fixed update bug.

# Version 7.0 #

* Improved search window, now it is possible to manage all the search key inserted, add, delete and save it from context menu.
* Improved window opening control.
* Some little bugs fixed.

# Version 6.9 #

* Implemented the recursive cities search with the valid system previously used in Weather_Plus Apixu version.
* Press f1 in the settings window for an explanation of the available commands.

# Version 6.8 #

* Updated compatibility for Python 3.

# Version 6.7 #

* Fixed a bug when it is tested a new city and using it in temporary mode by simply press "enter" and at a later time trying to add it via the "Add" button.
* Added abbreviation for SOUTH GEORGIA AND THE SOUTH SANDWICH ISLANDS to the database, but unfortunately at the moment it seems that the cities of this state do not work or have incomplete data, we hope it will be solved soon.

# Version 6.5 #

* Fixed a couple of bugs in sound effects reproduction; a couple of "for" cycles with incorrect maximum values caused the call to a non-existent sound effect.
* Fixed bug in local time in "details"; 12-hour time conversion gave an error.
* Fixed a bug in the Yahoo Weather Forecast report; in some cities the forecasts start from the previous day and not from the current one. The correction of these cities entails the loss of the last days of forecast proportionate to the mismatch of dates (if the forecast days are set to 10).

# Version 6.4 #

* Daylight saving time removed in the "Details" function.
* Improved audio effects reproduction; now they update regularly if the weather conditions change.

# Version 6.3 #

* Fixed encoding issues.

# Version 6.2 #

* Fixed bug in the "Add city" function.
* Fixed bug that did not assign the variable "_volume" when starting the addon.
* Added missing code from version 6.0; now you can recover the saved cities from the version that uses the Apixu API; the "Test" and "Remove" buttons and non-compatible cities are available in the format: "Ferrara, iter 44.83,11.58 0" (city, geographic coordinates, area definition).

# Version 6.1 #

* Fixed 2 bugs.

# Version 6.0 #

* Weather Plus returns to using the Yahoo Weather API.
* Virtually all the features of the previous version 4.8 are back and keeps the "Rename" button.
* Compatibility with Python 3.

# Version 5.0.1 #

* Fixed bug, that returned an empty string if the wind speed in mph was 0.
* Fixed bug that caused sound effects not consistent with the time zone to be reproduced.
* Adjusted the number of forecast days from 9 to 6 in readme.

# Version 5.0 #

* Weather Plus now uses the APIXU API.

# Changes in the Weather Plus Settings window #

* Removed old checkbox "State of barometric pressure". Replaced with new checkbox "Add cloudiness value";
* It gives you the percentage of cloudiness.
* Added new checkbox "Add precipitation value". It gives you the amount in millimeters of precipitation.
* Removed old checkbox "Indicates the wait with a beep while you search for the latest bulletin"; left active by default.
* Added the astronomic information;
* Time of moonrise and moonset.
* Added new button "Rename"; to rename cities more conveniently.
* Improved function of the "Test" button; now accept some commands to facilitate the search for cities; these new commands are described in the help function that can be called up with F1.

# Version 4.8 #

# Changes in the Weather Plus Settings window #

* Added new checkbox; "Use only weather effects"; this allows you to filter out all other environmental effects.
* Improved random playback and added 71 new sound effects; you will need to update them by clicking twice in "enable audio effects" checkbox.
* The volume type assigned by the user, between the general and current audio volume, is now maintained when the configuration is saved.
* Removed useless sound during selection text in edit box by pressing control+a.
* Improved readability into help window invokable with F1 function key.
* Added new compatibility flag for NVDA 2019.1, and the current alpha versions.

# Version 4.7.7 #

* Removed unnecessary notification of download complete when the update of Weather Plus.
* Added 6 new sound effects; it will be necessary to update them from the settings of the plugin.

# Version 4.7.6 #

* Bugfix release.

# Version 4.7.5 #

* Bugfix release.

# Version 4.7.3 #

* "Details" function was updated for convenience; the information about the altitude are now provided by veloroutes.org. This leads to small differences of little relevance.

# Version 4.7.2 #

* Fixed small encoding bug.

# Version 4.7.1 #

* Fixed bug when getting the information about the time zone.

# Version 4.7 #

* Simplified the update section; now at the start, in case an update is available it will be possible to proceed directly through a single dialog box.
* Removed the file selector in the update section; now the update file is saved to the temporary folder, it open the possibility to install the update automatically, good for beginners.

# Version 4.6.9 #

* Added Arabic localization (thanks to Wafik Immaculate).

# Version 4.6.8 #

* Updated localizations for Brazilian Portuguese and European Portuguese localizations (thanks to Alberto Mendonça).

# Version 4.6.7 #

* Improved the reading of the current time; in some cities, it was not correct. Added daylight saving time to the details; available only for the countries that adopt it.

# Version 4.6.5 #

* Fixed small bug when reading the time.

# Version 4.6.4 #

* Improved the reading of current local time; search keys are more accurate.

# Version 4.6.2 #

* Fixed bug: after a check for updates, the "set a temporary city..." menu was enabled even if there was no available list of cities.
* Fixed bug; unable to configure WP when the weather.ini has not been created yet,.

# Version 4.6 #

* Added the menu item "Set a temporary city..."; for the sake of completeness, now you can open the temporary city's list also from the menu.
* Improved management of temperature scale; now the settings window will always return the default value.
* Improved prevention of the multiple opening of the main windows; if one of these is already opened, in addition to the sound alert, puts it in foreground.
* Improved audio effects; now are based on the current local time from the city in use.

# Changes in details button function in settings window #

* Added current local time.
* Fixed altitude value; now return the altitude values when the value is less than or equal to zero.

# Version 4.5.5 #

* Correct localization and documentation in Serbian.
* Correct the German localization.

# Changes in the Weather Plus Settings window #

* Added new checkbox; you can enable the comma as the decimal separator, otherwise the separator will be the point.

# Version 4.5.3 #

* Correct 2 strings in Russian and Ukrainian localizations.
* Corrected title of the Check for upgrade window.
* Improved update algorithm.

# Version 4.5 #

* Added hotkey NVDA+shift+control+alt+w; it Opens the Weather Plus settings dialog.
* Correct some English strings.

# Changes in the Weather Plus Settings window #

* Added 8 new checkboxes; it is now possible to further customize the readout:
* Wind direction.
* Wind speed.
* Perceived temperature.
* Humidity value.
* Visibility value.
* Atmospheric pressure value.
* Indicates the atmospheric pressure in millimeters of mercury (mmHg).
* State of the barometric pressure.

# Version 4.4.8 #

* Added Polish translation (thanks to Zvonimir Staneczyć).
* Compatibility with wx python version 4.

# Version 4.4.1 #

* Added SSL support.

# Version 4.4 #

* Fixed bug in the reading of the new version string, during a connection time-out.
* Improved the upgrade section; now the dialog do not interferes with the nvda menu.
* Revised and corrected Russian localization.
* Adding Ukrainian translation (thanks to Alex Yeshanu).

# Version 4.3.4 #

* Revised and corrected German Localization.

# Version 4.3.3 #

* Added German localization (thanks to Karl Eick).

# Version 4.3.2 #

* Added Romanian localization (thanks to Florian Ionașcu).

# Version 4.3.1 #

* Fixed a minor bug in the function "details"; the strings "latitude" and "longitude" were reversed compared to the value.

# Version 4.3 #

* Weather Plus moved to the "nvda.it" as it's default hosting provider.

# Version 4.2.4 #

* Fixed a minor bug when the connection was not active.

# Version 4.2.3 #

* Now Weather Plus is able to run some connection attempts before notifying the malfunction of the WoeId in use, it emits a beep at each attempt; this beep, if you want, can be disabled by using a checkbox by Weather Plus settings.

# Version 4.2.2 #

* Fixed bug in the translation strings for the scale measurement. In some languages, Kelvin, Celsius and Fahrenheit have not been translated.

# Version 4.2.1 #

* Fixed update notice of Weather Plus during the Windows start-up; this happens when the button was pressed "Use currently saved settings on the logon and other secure screens (requires administrator privileges)" from the general settings of nvda, which copies the configuration, and all of the add-on folder systemConfig, but these are not synchronized with subsequent updates of the add-ons. If you have ever used at least once this option, you will have to do it again one last time just after to have up-to-date Weather Plus.

# Version 4.2 #

* Added 5 new sound effects; it will be necessary to update them from the settings of the plugin.
* Fixed bug in the import function; the list of cities was not sorted alphabetically.
* Added import mode in the import function; you may decide to completely replace your own list, or simply add new cities to it.
* Updated the reading of the weather forecast, current weather report; adding the perceived temperature (wind chill).
* Added new strings to the list weather reports.

# Version 4.1 #

* Fixed bug in the forecast for up to 10 days; now if the estimates received are in number less than the request of the user, the missing days are indicated as unknown.
* Fixed string help entry on the command nvda+shift+w.
* Revised and updated documentation.

# Version 4.0 #

* Updated some parts of code and replaced all instructions eval().

# Version 3.9.7 #

* Fixed bug during the reading of weather forecasts; now the temperatures are read correctly.

# Version 3.9.6 #

* Changed the rounding in the conversion of atmospheric pressure from mbar in inches of mercury; now the value is calculated in defect, while before it was in excess.

# Version 3.9.5 #

* Added 2 new strings to the list weather reports.
* Fixed 2 bugs.
* Updated running sounds for the effect in conditions of only wind; now the sound of the wind can vary randomly.

# Version 3.9.4 #

* Documentations, localizations for Croatian and German language were removed; because they are no longer supported by the respective translators.
* Fixed bug in Serbian localization.
* Updated Czech localization.
* Updated documentation and localization for Galician.

# Version 3.9 #

* Changed again API service; Weather Plus now uses the new Yahoo Weather API with language Yahoo!Query and JQuery:
* The api key is no longer required.
* Restored The search of the homonymous cities; it will be possible to choose exactly the desired city from a list.
* Optimized the output of general sounds; now they are synchronized with the voice synthesis and are faster.
* Improved the cache for data off-line; is zeroed every 10 minutes or only by changing the city.
* Barometric pressure measured in mbar, or in inches of mercury (if set to Fahrenheit).

# Version 3.8 #

* Data accuracy fixes.
* Enabled the automatic setting of the language; now the API sends the data of the weather conditions in the language set by nvda.
* Added the cache for bulletin and weather forecasts; if not changed the city, degree scale or the days of forecast set, you will be able to read the data for 10 minutes even when connection off-line. The cache is reset at each change described above. This is because the bulletins do not change in this period of time and to reduce the frequent calls to the API, maybe playing with sound effects.
* Improved searching for updates; now once downloaded, it will be activated to its installation, or in the case of a portable version of nvda it will be opened the folder where you saved the update.
* Updated all sounds; now the sounds are in the wav format.

# Version 3.7 #

* Added possibility to disable the conversion in meters per second of the wind.
* Added possibility to use units of measure in pounds per square inch.
* Fixed 2 bugs.

# Version 3.6 #

* Changed the API service (application programming interface); now WP uses the service offered by OpenWeatherMap.org instead of Yahoo Weather.com.
* Added Wind classification in the current bulletin.
* Added a cloudiness percentage in the current bulletin.
* Adopted the units of pressure measurement in hectopascal in the current bulletin.

# Changes to the Weather Plus Settings window #

* Changed insertion/search from yahoo zipcode/woeId in ID number, identifier of the city; ID numbers city are similar to woeid, but the woeId will no longer work, even the old zipcode. You will be able to rediscover a great part of the cities by typing the name or part of it.
* Added insertion/Search for geographical coordinates.
* Added insertion/search by postal code.
* Improved the function "details".
* Assigned to F1 key the entry/search help.
* Assigned to F4 key the controls to the forecasts from 1 to 16 days set. Attention, if you choose to copy to the clipboard a value greater than 10, it will not be read!
* Assigned F5 key for audio controls.
* Adding measurement scale degrees Kelvin.
* Added check for updates; you can set the control by settings or check manually from menu.
* Reassigned the button "Find your city" in "Management of your API Key..."; allows you to enter or change the key-API.

# Version 3.5 #

* Added Croatian translation (thanks to Gordan Radić).
* Added control for no longer valid WoeId and Zip Code found in the network; there have been reports of codes that have stopped working from one day to another, WP now warns if one of these has been inserted from the windows of search on the net. If this occurs using the function "Find your city...", please report it to me so that I can update the Weather_buffer and remove them from the list.
* Fixed encoding bug in the search functionality.
* Updated the window to set one temporary zip code; added feature "Find" As in the other windows of Weather Plus: Control+F3 = Find..., F3 = Find next, Shift+F3 = Find previous.

# Version 3.4 #

* Added Galician translation (thanks to Iván Novegil).
* Added Portuguese translation (thanks to Ângelo Miguel Abrantes).
* Added German translation (incomplete).

# Version 3.3 #

* Added the measure of the speed of wind in meters per second.
* Encoding fixes.

# Version 3.2 #

* Updated the reading of the weather forecast, current weather report and reading of the date of the current weather report; Yahoo weather forecast, from a bit of time and in random amounts, allows it to pass a historic from -10 to -5 days of weather forecast to be inserted between the updated data that we want to read; it was added a filter that allows you to read only the last weather data updated, and a discreet beep alerts when it intervenes; this beep, if you want, can be disabled by using a checkbox by Weather Plus settings. Obviously, the filtering of data sometimes involves a short delay in reply, but is still acceptable.
* Forecasts of the time extended to 10 days.

# Version 3.1 #

* Added translation in Serbian (thanks to the kind cooperation of Dejan Gasic).
* Fixed command insert+alt+w; it did not check the validity of the zipcode in use and did not check if the connection was active as the other commands do.
* Updated the playback function of sound effects; mp3 format is now used. Now the files will be much smaller.
* Added 55 new sound effects; it will be necessary to update them from the settings of the plugin.

# Changes to the Weather Plus Settings window #

* Fixed display help on the buttons; now disables / enables real-time through the appropriate checkbox.
* Added 3 shortcut commands to navigate more quickly in the window:
* F1 jumps into list and edit box of zip code.
* F2 returns to the last selection reached with TAB.
* F3 jumps into volume controls (if the sound effects are installed and activated).
* Added shortcut commands for all checkboxes and buttons; omitted the two radio buttons as they are present in succession and the first is reachable with the command control+shift+w.
* Changed, the button "define" is now disabled if the sound effects are not installed and activated.
* Added volume controls; you can adjust the overall volume and the last heard sound effect; this option is enabled if the sound effects are installed and activated.
* Added ability to set the system time in 12-hour format (12:30 AM `-` 12:30 PM) , or the 24-hour system (12:30 `-` 00:30).

# Version 3.0 #

* Added the Slovak translation (thanks to the kind cooperation of Vitek Jirasek).
* Added translation in Portuguese-Brazilian and Portuguese-Portugal (thanks to the kind cooperation of Adair Knaesel).
* Added new strings to the list weather reports.
* Added 171 new sound effects, now the total amount is 213.
* Added command insert+alt+w in the gesture to announce last update of current bulletin.
* Added scriptCategory which shifts in the correct position the rapid keys of Weather Plus in "Input gestures..."

# Changes to the Weather Plus Settings window #

* Added radio button to set how to indicate the temperature scale;
* The choice is between:
* Celsius `-` Fahrenheit
* C `-` F
* No indication
* Added button "Define"; it permits to define the zone of one city between:
* Hinterland
* Maritime area
* Desert zone
* Arctic zone
* Mountain zone
* The choice will consent to Weather Plus to use more appropriate sound effects for every single city; this is the reason for the boost of the number of new sound effects in this version of the addon; many of the new sound effects I got them from Tapin, whom I thank sincerely.

# Version 2.9 #

* Added option when importing to select the contents of the imported file.
* Four new sounds effects were added.
* Adding translation into Russian (thanks to Alex Yeshanu).
* Adding translation into Czech (thanks to Jirimu Holzingerovi).

# Version 2.8 #

* Fixed bug in "details", it used to open the window of the occurrences when he could not find the city.
* Fixed regexp to search for the altitude; it did not accept parameters of single digits.
* Improved parser of the edit box; it should find more easily the city.
* Connections now handled by urllib2, instead of urllib; this should allow the functioning of the addon even on a computer connected to the corporate network protected by proxy.
* Added feature "Find"; Control+F3 = Find..., F3 = Find next, Shift+F3 = Find previous.

# Version 2.7 #

* Fixed wrong name of a string "Motorcycle" in "Motorcycle00"; he asked updated sound effects because they could not find the file.
* Added ability to read about wind; direction, speed and temperature of the wind.
* Added ability to read atmospherical information; humidity, visibility, pressure and state of the barometric pressure.
* Added ability to read the Astronomic information; time of sunrise and sunset.

# Changes to the Weather Plus Settings window #

* Added 3 checkboxes to manage their information listed above.
* Added button "Details"; provides some information such as the real name of the city (assigned by Yahoo Weather Forecast), the state / region and the nation to which it belongs; with geographic coordinates, and height above sea level.
* Added recognition of WoeID (location codes, eg. Bologna it corresponds to 711080).
* Now you can type the name of the city, in this case, if any, the occurrences will be listed and you will be able to choose.

# Version 2.6 #

* The functions of the buttons "Add" and "Remove" were optimized in the zip code's list management; now the operation are a lot more fast!
* The function of the button "Test" was optimized, now it exploits until 13 research keys; Now if it doesn't find the name of the city it is a real bad luck!
* The function of the button "Find your city...", now finds more countries; it was added an automatic test that collects the functioning zip codes, and it further consents a rapid visualization thanks to the creation of a little buffer corresponding to the name of the specific country.
* Three new sounds effects were added; it will be necessary to update them from the settings of the plugin.

# Version 2.5 #

* Added command in the gesture to switch temporarily the temperature scale from Celsius to Fahrenheit, the command is also effective in the settings window.
* Fixed bug, if the user did not press the "Add" or "Preset" buttons, it did not allow to vocalize the name of the city since it was not included in the list.
* Added new strings to the list weather reports.

# Changes to the Weather Plus Settings window #

* Added button to open a research web page in order to check for the world-wide Zip Codes.
* Added the possibility to import / export the Zip Codes from friends.
* Added possibility to copy the weather report or the weather forecast to the clipboard.
* Added possibility to listen to the meteorological audio effects, the option also allows the installation / upgrade of the audio effects.
* Added ability help buttons on the management of Zip Code.
* Change to the display mode of the window, the menus of nvda are unrestrained when it is open.

# Version 2.4.4 #

* Added 2 new strings to the list weather reports.
* Adding translation into Spanish and French (thanks to Pablo Vargas and Rémy Ruiz).

# Version 2.4.3 #

* Adding up the weather forecast for the next 4 days.
* Adding a string to the list weather report.
* The list of temporary zipcode is now ordered to each new insertion.

# Version 2.4 #

* Fixed a bug that prevented to save and manage properly the city names containing accented vowels.

# Version 2.3 #
* Eliminated dialog box to set the scale of temperature measurement, has now been added a new gui that allows you to set all in one window.
* You will then also possible to test / add / delete / preset as the default Zip Code collected as a list.
* Modified the dialog box for entering typed a Zip Code, now in temporary mode allows you to set a Zip Code previously added to the list in Preferences from the menu.
* Now the documentation can be read in English if the language setting is not included in the documents.

# Version 2.2 #

* Fixed bug that did not allow you to open the documentation for the definitive versions of NVDA.

# Version 2.1 #

* Fixed a bug that did not close properly the plugin, this prevented the NVDAupdate the icon in the system tray.

# Version 2.0 #

* Weather Plus Settings menu in Preferences submenu moved.
* Correct input on the fly is no longer saved, so it is temporary; to call the city set in the preferences, press NVDA+control+f3.

# Version 1.9 #

* Added help entering functions.
* Added a new function for quick entry of Zip Code.
* Added read / write configuration weather.ini, now no longer need to edit the source file.
* Weather menu added in the System Tray.
* Added setting submenu Zip Code .
* Added sub-setting temperature scale (Fahrenheit or Celsius).
* Added menu Documentation.
* Added Italian localization.

# Initial Version 1.1 #

* Updated the NVDA-addon.
* Translation support has been added.

--------------------------------------------------------------------------------

[1]: https://addons.nvda-project.org/files/get.php?file=wetp
