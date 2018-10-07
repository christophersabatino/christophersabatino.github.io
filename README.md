# christophersabatino.github.io

Convert this README.md version to DEVELOPMENT.md or SETUP.md when the time is right.

## GITHUB SETUPS:
https://gist.github.com/TylerFisher/6127328#file-hosting-on-github-md

https://gist.github.com/TylerFisher/6127328#steps-for-hosting-a-website-on-github

https://medium.com/@svinkle/publish-and-share-your-own-website-for-free-with-github-2eff049a1cb5

https://codeburst.io/how-to-get-your-website-online-easily-with-github-44ea5ce2997d

https://github.com/christophersabatino/christophersabatino.github.io/settings
- https://help.github.com/articles/using-a-custom-domain-with-github-pages/

## GOOGLE DOMAINS
https://support.google.com/domains/answer/4632243

https://domains.google.com/m/registrar/transfer/in/christophersabatino.com?hl=en-US

https://help.hover.com/hc/en-us/articles/217281737-How-to-Transfer-a-domain-from-Network-Solutions


## NVM:

## NODE:

## NPM:




### ISSUES & WORKAROUNDS:

#### WHAT: Terminal says... "xcrun: error: ..."
Terminal:
``` javascript
$ git status
xcrun: error: invalid active developer path (/Library/Developer/CommandLineTools), missing xcrun at: /Library/Developer/CommandLineTools/usr/bin/xcrun
```
##### SOLUTION:
"Now, the issue here is that the command line tools are either missing or broken. The same happened after El Capitan, so this appears to be a general issue and one that, sadly, Apple don’t seem to fix.

The solution is simply to re-install the required software again. Open up a Terminal window and type the following…"

```
$ xcode-select --install
```

- https://malucelli.net/2015/10/01/missing-xcrun-on-os-x-el-capitan/

- https://artiss.blog/2016/08/xcrun-error-after-macos-sierra-beta-installation/
