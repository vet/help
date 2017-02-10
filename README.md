# Help

Automatic help command for your scripts directory.

## Usage

To start, put [help](https://github.com/vet/help/blob/master/help) into your projects `scripts` directory.

Somewhere near the top of all of your scripts, put a comment at the top that briefly describes what the script does, like so:

```sh
## Uploads the source to the production server
```

This comment must immediatly follow two pounds and a space: `## `.

If your script is not in a language that comments with pound signs, don't worry, this also works:

```js
// ## Uploads the source to the production server
```

Now that everything is all setup, calling the `help` script outputs something that looks like this:

![Sample Output](https://cloud.githubusercontent.com/assets/2105067/22812972/14f652e6-ef16-11e6-87d8-149bc276d3a7.png)

## License

[MIT](LICENSE.md)
