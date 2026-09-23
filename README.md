# ecureuil-discovery-sources
This is the repository that contains all the sources that will be available to be seen in Discovery Sources in the Ecureuil client.

## I'm a developer, how do I add mine?
You can use the sources.jsone file in the root as an example, or mine inside Sources/fratta.json.

Each developer must create their own json file, possibly with their name as name of the JSON. Inside a JSON, you can add all your sources in one file. Two requisites:
- the ID must be the same as the one in your source; this is because Ecureuil checks for IDs inside the client
- the URL must be the same as your sources.json
- the name in your JSON will be the name shown in Discover Sources. For consistency, it must be the same name as the one in your source

To have your repository available there, you can submit a merge request, and once I apply the merge request, it'll be available. The GitHub job will merge all JSONs from folders inside a single JSON.

## What are the sources available for now?
As of **23th September 2026**, here are the sources available. Under sources.json URL, you can directly copy the link to put it inside Ecureuil.

|Icon|Name|Description|sources.json URL|Author URL|
|-|-|-|-|-|
|<img src="https://avatars.githubusercontent.com/u/87281326?v=4" width="50">|Fratta's Ecureuil source|This is fratta's Ecureuil personal source, with my own apps that I made over the years for Windows (btw, I'm the developer of Ecureuil too)|[URL](https://fraaaaa4.github.io/Ecureuil-fratta-apps/sources.json)|[URL](https://github.com/fraaaaa4)|
|<img src="https://avatars.githubusercontent.com/u/30177186?v=4" width="50">|hamed7ir's Ecureuil source|ARM32 applications for Windows RT and Windows 10 ARM32, built and tested on Surface RT and Surface 2 hardware.|[URL](https://hamed7ir.github.io/ecureuil-hamed7ir-apps/sources.json)|[URL](https://github.com/hamed7ir)|
