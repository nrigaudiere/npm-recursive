# npm-recursive

##### Recursively run npm in a folder

Takes your tree and checks for package.json in every folder and runs `npm` in every folder.

### Arguments

You can add arguments when running the command

```
$ npm-recursive --cmd upgrade
npm upgrade v1.1.0
success All of your dependencies are up to date.
Done in 0.22s.

Current npm path: YOUR_PATH/npm-recursive/package.json...
End of npms

```

```
$ npm-recursive --cmd upgrade --opt <package-name>
```
