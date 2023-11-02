# Project 7
I spent so much time on this but ran into problem after problem

# Internet note taking app

QuickNotes is a user-friendly and efficient note-taking app designed to help users capture their thoughts, ideas, and important information on the go.
With a minimalist and intuitive interface, users can easily create, edit, and organize their notes to enhance productivity and keep their thoughts organized.

## Functionality 

The following **required** functionality is completed:

* [x] Uses Firebase realtime database correctly 
* [x] Correct layout for MainScreen
* [x] Correct layout for RecyclerView 
* [x] Uses Firebase authentication
* [x] UserScreen is implemented correctly
* [x] Implements addValueEventListener to update the RecyclerView
* [ ] Menu items and listeners
* [ ] Shows Dialog to confirm 
* [x] Initial prompt to login/signup
* [ ] Application does not crash 
* [x] Appropriate comments
* [x] READme.md 


## Video Walkthrough


Made by LiceCap

## Notes

Set up firebase database and auth on the server side and connected them to the app,
and I can see the app making pull requsts, but no data was ever getting to my app,
the log.d wouid never fire in line 52 of the main activity.

For some unknown reason my xml layout files would not recognize my kotlin files, 
making it impossible to run any screens excluding the home screen.

Despite this, I beleive that my realtime firebase, mainscreen layout, recyclerview layout,
firebase authentication, and userscreen deserve 80% each

## License

    Copyright 2023 Samuel Stazinski

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
