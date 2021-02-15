# awsm-cli

A bash script to search [Awesome List](https://github.com/sindresorhus/awesome)
from the command-line.

## Usage

```
Usage:
awsm-cli
         -b  Browser to open the URL
         -r  Search awesome list through rofi
         -f  Search awesome list through fzf
         -u  Update awesome list repository
         -h  help
```

* Search for a particular project from the awesome list using rofi and open the URL in the
    default browser

```
  awsm-cli -r

```

* You can specify a default browser in the script

```
 awsm-cli
 AWESOME_JSON_REPO="Awesome.json"
 BROWSER="{DEFAULT_BROWSER}"
```

* Or you can specify a custom browser while running the command

```

awsm-cli -r -b firefox

```


## Requirements

* [rofi](https://github.com/DaveDavenport/rofi)
* [fzf](https://github.com/junegunn/fzf)
* [git](https://git-scm.com/)
* [jq](https://github.com/stedolan/jq)
* sed
* bash
