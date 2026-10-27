# The Noted

An offline-first notes app built with Flutter. Optional cloud backup is
available on supported platforms.

[![Say Thanks!](https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg)](https://saythanks.io/to/mohak1283)

## Show some :heart: and star the repo to support the project.

**Complete UI Contains:**

► Sign in & Sign up
► Home Screen
► Setting screen
► Account details
► Appearance setting
► Add note screen
► Edit note screen

## Note
This repository is still under development and I will continue to add more features to it.

## Features

 * Create, edit, and delete notes offline without signing in
 * Save notes and audio recordings on the device
 * Attach images, videos, and documents to notes (up to 200 MB per file)
 * Copy, cut, and paste note text
 * Adjust note text size, choose a note color, and add tags
 * Print notes or save them through the system print dialog
 * Optionally sign in from Account to back up and sync notes
 * login and sign up user
 * View notes in list or grid layout
 * Change app theme - light or dark theme
 * Add and edit notes
 * Record and play audio notes
 * Colorful notes (random)

## Windows desktop app

The Windows build works offline and stores notes on the local computer. Cloud
sign-in and sync are currently only configured for web, Android, and iOS.

To build a standalone Windows release, install Visual Studio 2022 with the
**Desktop development with C++** workload and a Windows 10/11 SDK, then run:

```powershell
flutter pub get
flutter build windows --release
```

Distribute the complete `build\windows\x64\runner\Release` folder. Run
`TheNoted.exe` from that folder; the executable depends on the DLLs and `data`
directory beside it.

## Screenshots
<p>
<img src="https://user-images.githubusercontent.com/38410384/122596221-2b447080-d087-11eb-96ff-e8797d46bdd5.png" alt="login screen" width = "250" >
<img src="https://user-images.githubusercontent.com/38410384/122596212-297aad00-d087-11eb-9de9-4b5acada4e6f.png" alt="dark sign up"width = "250" >
<img src="https://user-images.githubusercontent.com/38410384/122596216-2a134380-d087-11eb-83fb-c2cf91fb675c.png" alt="home grid view" width = "250">
<img src="https://user-images.githubusercontent.com/38410384/122596209-28e21680-d087-11eb-9b19-cdb729729f11.png" alt="dark home screen" width = "250" >
<img src="https://user-images.githubusercontent.com/38410384/122596200-254e8f80-d087-11eb-8be2-c452f748c70a.png" alt="add note" width = "250">
  
<img src="https://user-images.githubusercontent.com/38410384/122597737-71023880-d089-11eb-897f-3a0993236281.png" alt="setting" width = "250">
<img src="https://user-images.githubusercontent.com/38410384/122596214-2a134380-d087-11eb-8836-ccb46aca5b68.png" alt="device setting" width = "250">
  
<img src="https://user-images.githubusercontent.com/38410384/122597989-d2c2a280-d089-11eb-8cc8-45b807fb51b8.png" alt="device setting" width = "250">
<img src="https://user-images.githubusercontent.com/38410384/122597732-6f387500-d089-11eb-8417-133f8401cd4b.png" alt="device setting" width = "250">
  
</p>


# Upcoming Features
 - To let user select note bg color
 - share notes
 - hand free note taking (speech to text) 
 
 ### Created & Maintained By

Tenzin Tamdin

<a href="https://twitter.com/ttamdin5"><img src="https://user-images.githubusercontent.com/35039342/55471524-8e24cb00-5627-11e9-9389-58f3d4419153.png" width="60"></a>
<a href="https://www.linkedin.com/in/tenzintamdin592/"><img src="https://user-images.githubusercontent.com/35039342/55471530-94b34280-5627-11e9-8c0e-6fe86a8406d6.png" width="60"></a>

> If you found this project helpful or you learned something from the source code and want to thank me, consider buying me a cup of :coffee:
>
> * [PayPal](https://www.paypal.com/paypalme/TenzinTamdin/)


## How to Contribute
1. Fork the the project
2. Create your feature branch (git checkout -b my-new-feature)
3. Make required changes and commit (git commit -am 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create new Pull Request

## License

    Copyright (c) 2021 Tenzin Tamdin
    
    Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
    
    The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
    
    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
