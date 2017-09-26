## react-web-part-demos

Branched off Eoverfield and included some more webparts created by other individuals and me.

### Building the code

```bash
git clone the repo
npm i
npm i -g gulp
gulp
gulp trust-dev-cert
gulp serve
```

This package produces the following:

* lib/* - intermediate-stage commonjs build artifacts
* dist/* - the bundled script, along with other resources
* deploy/* - all resources which should be uploaded to a CDN.

### Build options

gulp clean
gulp test
gulp serve
gulp bundle
gulp package-solution

### Important cmds

```bash
Fabric React:
npm --save install office-ui-fabric-react
gulp trust-dev-cert
yo @microsoft/sharepoint
```

## Webparts ##

1) Image Magnifier

![Image Magnifier](https://raw.githubusercontent.com/CodeHeight/TypeScript-Examples/master/images/solarsystem.png)

2) Weather

![Weather](https://raw.githubusercontent.com/CodeHeight/TypeScript-Examples/master/images/weather.png)

3) Temp fix for Chart.js

![Chart cmd Error](https://raw.githubusercontent.com/CodeHeight/TypeScript-Examples/master/images/cmd00.png)

![Chart Error](https://raw.githubusercontent.com/CodeHeight/TypeScript-Examples/master/images/chartjs.png)

