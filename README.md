# Project 1 - _Todo_

**Todo** is an android app that allows building a todo list and basic todo items management functionality including adding new items, editing and deleting an existing item.

Submitted by: **Carmina Edrozo**

Time spent: **5** hours spent in total

## User Stories

The following **required** functionality is completed:

- [x] User can **view a list of todo items**
- [x] User can **successfully add and remove items** from the todo list
- [x] User's **list of items persisted** upon modification and retrieved properly on app restart

The following **optional** features are implemented:

- [x] User can **tap a todo item in the list and bring up an edit screen for the todo item** and then have any changes to the text reflected in the todo list

The following **additional** features are implemented:

- [ ] TBA, work in progress

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://i.imgur.com/uIEc40w.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while building the app.

- Challenge 1: When dragging the button to a desired location, it would not stay and it would go back to upper left corner.

  Solution: Press magnet icon to disable autoconnection to parent

- Challenge 2: I would get an ADB error. "The ADB binary found is obsolete and has serious performance problems..."

  Solution: Install newest version of Android SDK Build-Tools

- Challenge 3: Making the class ItemsAdapter was confusing at first

  Solution: Read more information about RecyclerView

- Challenge 4: Workflow of adding a new feature. How intent, extras and other features connect together.

  Solution: Drew the workflow so I know what's going on.

- Challenge 5: Organization is not good but I am not sure how to properly organize it. Would love to separate some functions or code to a separate file so it's cleaner.

## License

    Copyright 2020 Carmina Edrozo

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
