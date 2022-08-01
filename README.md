
## ANDROID SIMPLE NOTE APPLICATION
You can use this application with no internet connection. This Application is not complex.
### Used Libraries
- androidx.appcompat:appcompat:1.1.0
- com.google.android.material:material:1.0.0
- androidx.navigation:navigation-fragment:2.2.0-alpha03
- androidx.navigation:navigation-ui:2.2.0-alpha03 
- com.android.support:preference-v14:28.0.0

### Screenshot
<img src="https://user-images.githubusercontent.com/46759371/67642919-f455a000-f921-11e9-935a-5e32687e451f.png"
width="210"
alt="Android Simple Note 1"/>
<img src="https://user-images.githubusercontent.com/46759371/67642929-15b68c00-f922-11e9-8d7d-17030e694f9a.png"
width="210"
alt="Android Simple Note 2"/>
<img src="https://user-images.githubusercontent.com/46759371/67642969-7ba31380-f922-11e9-874c-204d6e51ecf2.png"
width="210"
alt="Android Simple Note 3"/>
<img src="https://user-images.githubusercontent.com/46759371/67642970-7ba31380-f922-11e9-8c73-4ca2787bf3a2.png"
width="210"
alt="Android Simple Note 4"/>

### Used Activities and Fragments
- MainActivity: Used Main activity.
  - Notes Fragment: Lists normal note and archive notes.
  - AddandNoteFragment: Used for editing and adding notes.
  - SettingFragment: Used for settings page.
- Pin Activity: Activity used when the pin is active.
### Model Classes
- Note: Note is the model  class.
- NoteDatabase: The Sqlite database class
- RecylerAdapter: Recyclerview adapter class
- Settings: Classifies the settings that are saved with the preferences "shared preferences ”object.
### Ui Classes
- ThemeManager: A class that prepares theme colors at application launch and makes theme changes.

<br><br>
