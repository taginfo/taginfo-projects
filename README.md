
# Taginfo Projects

This repository contains the list of projects for taginfo. See

https://wiki.openstreetmap.org/wiki/Taginfo/Projects

## Notes for contributors

To add you project add a line to `project_list.txt` with a unique ID and the
link to your JSON project file.

### Choosing a unique ID

The unique ID MUST NOT contain any characters except lower case latin letters
(a-z) and the underscore (\_). Usually it will reflect your domain name or the
type of map. Look at the other IDs for some ideas.

### Adding to the project list file

Please add your line at the correct place so the file keeps its alphabetical
ordering. This makes it easier for others to create unique IDs.

### Hints about generating parts of the taginfo.json file

If you have a [list of keys](https://github.com/ypid/opening_hours.js/blob/master/related_tags.txt) your project does support you might want to look at [ypid][]’s [NodeJS script](https://github.com/ypid/opening_hours.js/blob/master/gen_taginfo_json.js) which can take a template JSON file and a list of keys and merge it into one `taginfo.json` file.

[ypid]: https://github.com/ypid
