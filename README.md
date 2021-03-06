# react-lib-starter
## Introduction
This project is for reducing scaffolding library project(babel, webpack, example project, etc)
## Clone the project
```
$ git clone https://github.com/suhanlee/react-lib-starter.git
```
## Setup
First, you should execute setup
```
$ npm run setup
> yarn && cd example && yarn

yarn install v1.16.0
warning package-lock.json found. Your project contains lock files generated by tools other than Yarn. It is advised not to mix package managers in order to avoid resolution inconsistencies caused by unsynchronized lock files. To clear this warning, remove package-lock.json.
[1/4] 🔍  Resolving packages...
success Already up-to-date.
✨  Done in 0.34s.
yarn install v1.16.0
[1/4] 🔍  Resolving packages...
success Already up-to-date.
✨  Done in 0.61s.
```
## Start
`babel` --watch option tracking changes lib files

`example` project is based on `creact-react-app`. So You can apply it and test it using just watch option. 
```
$ npm run start
You can now view example in the browser.

  Local:            http://localhost:3000/
  On Your Network:  http://192.168.84.23:3000/

Note that the development build is not optimized.
To create a production build, use yarn build.
```
## Write code!
```
import React from 'react'

class DummyLib extends React.Component {
    render() {
        return(
            <div>
                DummyLib
            </div>
        )
    }
}
export default DummyLib;
```

## Build Library
You can build library
```
$ npm run build:lib
```