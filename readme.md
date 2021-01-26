# rofi-awsm

A bash script to search [Awesome](https://github.com/sindresorhus/awesome)
list by using [rofi](https://github.com/DaveDavenport/rofi).


## Features

* Search for an particular project from the awesome list

```
  rofi-awsm -s
```

* Specify your default browser in the script itself at the top

```
 rofi-aswm
 AWESOME_JSON_REPO="Awesome.json"
 BROWSER="{DEFAULT_BROWSER}"
```

* Specify your custom browser

```
rofi-awsm -s  -b firefox
```


## Requirements

* [rofi](https://github.com/DaveDavenport/rofi)
* [git](https://git-scm.com/)
* [jq](https://github.com/stedolan/jq)
* sed
* bash
