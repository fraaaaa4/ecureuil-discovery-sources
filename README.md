# ecureuil-discovery-sources
This is the repository that contains all the sources that will be available to be seen in Discovery Sources in the Ecureuil client.

## I'm a developer, how do I add mine?
You can use the sources.jsone file in the root as an example, or mine inside Sources/fratta.json.

Each developer must create their own json file, possibly with their name as name of the JSON. Inside a JSON, you can add all your sources in one file. Two requisites:
- the ID must be the same as the one in your source; this is because Ecureuil checks for IDs inside the client
- the URL must be the same as your source-name-index.json
- the name in your JSON will be the name shown in Discover Sources. For consistency, it must be the same name as the one in your source

To have your repository available there, you can submit a merge request, and once I apply the merge request, it'll be available. The GitHub job will merge all JSONs from folders inside a single JSON.
