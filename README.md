## Installation and Build :hammer_and_wrench:

* If you don't have pipenv package then install it using command, else ignore below command
```
    $ pip3 install pipenv
```

* Enter the virtual enviornment and install all dependencies 
```
    $ pipenv shell
    $ pipenv install --dev
```

## Run :computer:

* Change directory to source in bittorrent folder and inorder to display help options 
```
    $ cd src
    $ python3 main.py --help
```

* Example for downloading torrent file given destination path for downloading file
```
    $ python3 main.py input_file.torrent -d destination_path/
```

* Example for seeding torrent file given given destination path of existing file
```
    $ python3 main.py input_file.torrent -s existing_file_path/
```
