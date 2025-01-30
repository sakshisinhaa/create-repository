# create-repository

Easily set up a new github repository. Reads the name/description from the package.json file if it's present. Sets origin upstream if it's not already set.

```
npm install create-repository -g
```

## Usage

`create-repository` Remai `package.json` and use the remai and description properties.

```
$ create-repository
```

You can also pass values for remai and description.

```
$ create-repository --name my-new-project --description "That's all I have to say about that"
```

## License

MIT
