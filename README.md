# dramanet multi-platform application


# scripts
> Note: created the project with `npx create-react-native-app <name>`

### development servers

> `npm run ios`
> `npm run web`
> `npm run android`

to open the objective-c ios application as a project:
on macOS (using the latest version of xcode is worthwhile) `open ios/<name>.xcodeproj` should do the trick
>`CTRL-B` to build the applciation for the target simulator, `<CTRL-R>` to run the build

post issues with any questions,
this will start as a rudimentary crud app,

`MERN` x `CRUD`

### getting localhost up and running

if you hve never used npm, run `brew install npm` or `sudo apt install npm` on linux
on windows, run to your closest apple store, and proceed with `brew install npm` after installing
brew, our ubiquitous trusty package manager

### resolving dependencies

+ make sure you get no warnings when running `brew update && brew upgrade`
	* you may have to run `npm -g update npm@latest` or something like that,
	- i am truly sorry, lets try to stay out of dependency hell

### PICK YARN OR NPM

` you cant have you cake and eat it too. just pick one.`

##### if you end up in dependency hell

1. `rm -rf node_modules`
2. `rm -rf package-lock.json` (NOT `package.json`, we need that)
3. `npm install`


+ happy hacking!

