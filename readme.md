# rofi-awsm

A bash script to search [Awesome](https://github.com/sindresorhus/awesome)
list by using [rofi](https://github.com/DaveDavenport/rofi).

## Usage

```
Usage:
Rofi - Awesome List
         -b  Browser to open the URL
         -s  Search awesome list
         -u  Update awesome list repository
         -h  help

```

* Search for a particular project from the awesome list

```
  rofi-awsm -s
```

* You can specify your default browser in the script itself

```
 rofi-aswm
 AWESOME_JSON_REPO="Awesome.json"
 BROWSER="{DEFAULT_BROWSER}"
```

* Or you can specify your custom browser while running the command

```
rofi-awsm -s  -b firefox
```


## Requirements

* [rofi](https://github.com/DaveDavenport/rofi)
* [git](https://git-scm.com/)
* [jq](https://github.com/stedolan/jq)
* sed
* bash
