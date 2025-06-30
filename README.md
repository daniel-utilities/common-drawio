<!--
    NOTE: To preview this file in VSCode, press F1 and run:
    "Markdown: Open Preview to the Side".
-->


# [![daniel-utilities/][icon_daniel-utilities]][home_daniel-utilities]  common-drawio

##### A common library of Draw.IO (Diagrams.net) objects

<!-- OPTIONAL: Add Title Image -->
<!--
![Title image alt-text](res/gallery/title.png "Title image mouseover text")
-->

<br/>



## Installation

### As a standalone library

01. In a terminal window, clone this repo to your system *with submodules*:

    ```
    git clone --recurse-submodules https://github.com/daniel-utilities/common-drawio.git
    ```

    If you already cloned the repository without ```--recurse-submodules```, you'll
    need to run the following from the root directory of the repository:

    ```
    git submodule update --init --recursive --remote
    ```

01. Open your Draw.IO/Diagrams.net app.
    Go to ```File --> Open Library``` and navigate to the ```common-drawio/src/{LIBRARY}.xml```.



### As a Git Submodule in an existing project

01. In a terminal window, run from the existing project's root directory:

    ```
    mkdir lib
    git submodule add -b main git@github.com:daniel-utilities/common-drawio.git lib/common-drawio
    git submodule update --init --recursive --remote
    ```

01. Add the following line to ```.gitconfig``` to ensure ```git pull``` pulls
    changes to submodules as well:

    ```
    submodule.recurse = true
    ```

### VSCode Integration

01. Add the following lines to your project's ```.vscode/settings.json```:

    ```
    "hediet.vscode-drawio.offline": true,
    "hediet.vscode-drawio.codeLinkActivated": true,
    "hediet.vscode-drawio.globalVars": {},
    "hediet.vscode-drawio.plugins": [],
    "hediet.vscode-drawio.knownPlugins": [],
    "hediet.vscode-drawio.customLibraries": [],
    "hediet.vscode-drawio.appearance": "automatic",
    "hediet.vscode-drawio.customColorSchemes": [],
    "hediet.vscode-drawio.customFonts": [],
    "hediet.vscode-drawio.theme": "automatic",
    ```

01. In ```.vscode/extensions.json```:

    ```
    "recommendations": [
        "hediet.vscode-drawio"
    ]
    ```

    Then ensure the extension is downloaded and installed.




<br/>


---
*Author: Daniel Kennedy* ([GitHub][home_danielk-98])

<br/>



<!-- Reference Links -->
<!-- DO NOT MODIFY! -->
[home_danielk-98]: https://github.com/danielk-98?tab=repositories
[home_daniel-templates]: https://github.com/orgs/daniel-templates/repositories
[home_daniel-contrib]: https://github.com/orgs/daniel-contrib/repositories
[home_daniel-experiments]: https://github.com/orgs/daniel-experiments/repositories
[home_daniel-hardware]: https://github.com/orgs/daniel-hardware/repositories
[home_daniel-robotics]: https://github.com/orgs/daniel-robotics/repositories
[home_daniel-utilities]: https://github.com/orgs/daniel-utilities/repositories
[icon_danielk-98]: https://avatars.githubusercontent.com/u/78428703?&s=60 "Github User: danielk-98"
[icon_daniel-templates]: https://avatars.githubusercontent.com/u/132400164?s=60 "Github Organization: daniel-templates"
[icon_daniel-contrib]: https://avatars.githubusercontent.com/u/107002767?s=60 "Github Organization: daniel-contrib"
[icon_daniel-experiments]: https://avatars.githubusercontent.com/u/111267723?s=60 "Github Organization: daniel-experiments"
[icon_daniel-hardware]: https://avatars.githubusercontent.com/u/111267783?s=60 "Github Organization: daniel-hardware"
[icon_daniel-robotics]: https://avatars.githubusercontent.com/u/107002723?s=60 "Github Organization: daniel-robotics"
[icon_daniel-utilities]: https://avatars.githubusercontent.com/u/107002832?s=60 "Github Organization: daniel-utilities"
