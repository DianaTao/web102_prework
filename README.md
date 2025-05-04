# WEB102 Prework - *Sea Monster Crowdfunding*

Submitted by: **Yifei Tao*

**Sea Monster Crowdfunding** is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: **8** hours spent in total

## Required Features

The following **required** functionality is completed:

* [X] The introduction section explains the background of the company and how many games remain unfunded.
* [X] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [X] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [X] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented features:

<img src='https://i.imgur.com/ymRaTts.mp4' title='Video Walkthrough' width='' alt='Video Walkthrough' />

<!-- Replace this with whatever GIF tool you used! -->
GIF created with Kap 
<!-- Recommended tools:
[Kap](https://getkap.co/) for macOS
[ScreenToGif](https://www.screentogif.com/) for Windows
[peek](https://github.com/phw/peek) for Linux. -->

## Notes

Describe any challenges encountered while building the app.
One of the main challenges I encountered while building the app was managing DOM manipulation effectively, especially ensuring that elements were properly selected, updated, and cleared before rendering new content. For example, forgetting to call deleteChildElements() led to duplicated game cards when switching filters. Using JavaScript methods like filter, reduce, and template literals also required careful attention, particularly when calculating totals or displaying grammatically correct summaries with the ternary operator. Additionally, wiring event listeners to the correct buttons and ensuring each click produced the intended filtered view took some trial and error. Overall, getting the logic, structure, and interactivity to work together smoothly was a rewarding but detailed process.

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
