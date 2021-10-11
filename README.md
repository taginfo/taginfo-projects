
# Taginfo Projects

This repository contains the list of projects for taginfo. See

* [JSON schema](https://github.com/taginfo/taginfo-projects/blob/master/taginfo-project-schema.json)
* [Description on Wiki](https://wiki.openstreetmap.org/wiki/Taginfo/Projects)
* [Projects table](https://taginfo.openstreetmap.org/projects)
* [Fetch status table](https://taginfo.openstreetmap.org/taginfo/projects)

[![Build Status](https://github.com/taginfo/taginfo-projects/workflows/Test/badge.svg?branch=master)](https://github.com/taginfo/taginfo-projects/actions)

## Notes for contributors

To add your project, add a line to `project_list.txt` with a unique ID and the
link to your JSON project file.

### Choosing a unique ID

The unique ID MUST NOT contain any characters except lower case latin letters
(a-z), the numbers (0-9) and the underscore (`_`). The first character must be
a letter. Usually it will reflect your domain name or the type of map. Look at
the other IDs for some ideas.

### Adding to the project list file

Please add your line at the correct place so the file keeps its alphabetical
ordering. This makes it easier for others to create unique IDs.

### Testing

Your pull request will be tested with GitHub Actions.

List of things which are tested:

* Is the `project_list.txt` sorted?
* Is the ID valid?
* Does the URL refer to a valid JSON file?

You can run this test before submitting the pull request with

    ./test_changes
