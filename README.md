# garmin-web
Sample web response for Garmin Connect IQ

1. Create a new file to contain the fake web response
    1. Create New File | "/docs/test.htm"
    1. In the file, enter the text "Hello World"
    1. Commit changes
1. Enable GitHub Pages for this repository
    1. Go to Settings | GitHub Pages
    1. Select **master branch /docs folder* in the **Source** dropdown
    1. Navigate to https://montaef.github.io/garmin-web/test.htm on a web browser
1. Since GitHub pages can't do x-www-form-urlencoded for garmin makeWebRequest, create a db.json file for https://my-json-server.typicode.com/ instead! typicode was used in original SDK example.
1. access fake JSON object at https://my-json-server.typicode.com/montaef/garmin-web/montaef

1. Congratulations, all done for now
