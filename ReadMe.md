# SuperNET Docs

This SuperNET Docs repository is for Iguana testers.

To make life of Iguana API testers, there pre-compiled binaries included with this repository.

#### OS X Platform Testers:
- Open command line Terminal app
- Change directory to `iguana/` and execute `./iguana_osx`

#### Linux Platform Testers:
- Open command line Terminal
- Change directory to `iguana/` and exuecute `./iguana_unix`


## Start testing iguana API:
- After starting **iguana** for your platform start web browser and visit http://127.0.0.1:7778
- It will display a web page with with SuperNET API list. You can use the input fields there to fill the data and submit to get results.


Under directory **iguana/help/** you'll find many **.json** files relating to the iguana API names.
The json fileds are pretty self explanatory. You can open these .json files and edit the description.
- To make life easier to edit these json files, you can copy the content of the json file, and paste it in online json editor such as http://jsoneditoronline.org.
- There edit the description in right side pane and update the left side pane's json code.
- Update the .json file contents, save it, and when done make a pull request to update the SuperNET Docs repository.

#### It's advised to use the online json editor as of these reasons:
- It asures that the json format you are submitting is correct.
- You can use [Github markdown] (https://guides.github.com/features/mastering-markdown/) in description which you'll put in .json fields.
- online json editor makes sure the markdown code you make does not break the json format, and still keep the markdown working code in description.


## Previewing iguana API Docs with slate
[Slate] (https://github.com/tripit/slate) is used for Documentation writing. Whatever updates you make to the .json files, are compiled to a file named **_API.md** which is found under **iguana/** directory.

This **_API.md** file needs to be replaced or update at **slate/source/includes/** if you want to preview it with slate.

There are few steps to update **_API.md**:
- When you test and update iguana API information in .json files, and wants to update the **_API.md** file, just delete the **iguana/index7778.html** file.
- Now refresh or revisit the address http://127.0.0.1:7778
- Visiting this link will regenerate the iguana/index7778.html file and also update the relative other files in iguana/ directory.

To preview the slate documents, you will first need to install slate. For that execute these commands from directory **slate/**:

```shell
# Make sure to have ruby-dev and nodejs package installed.
# Not having ruby-dev gave issues installing ffi gem package

sudo apt-get install ruby-dev nodejs

# either run this to run locally
bundle install
bundle exec middleman server

# OR run this to run with vagrant
vagrant up
```

You can now see the docs at http://localhost:4567 or http://127.0.0.1:4567.

You can also make static html pages of the so far docs by executing `./deploy.sh`. It's totaly option if you want to build the static html files or not.

Join [SuperNET Slack] (http://slackinvite.supernet.org) #iguana channel to keep updated with iguana development and get help on iguana API.


