
# Notes for contributors

To add you project, add a line to [project_list.txt](project_list.txt) with a unique ID and the
link to your JSON project file.

## Choosing a unique ID

The unique ID MUST NOT contain any characters except lower case latin letters
(a-z), the numbers (0-9) and the underscore (`_`). The first character must be
a letter. Usually it will reflect your domain name or the type of map. Look at
the other IDs for some ideas.

## Adding to the project list file

Please add your line at the correct place so the file keeps its alphabetical
ordering. This makes it easier for others to create unique IDs.

## Testing

Your pull request will be tested with Travis CI.

List of things which are tested:

* Is the `project_list.txt` sorted?
* Is the ID valid?
* Does the URL refer to a valid JSON file?

You can run this test before submitting the pull request with

    ./test_changes

