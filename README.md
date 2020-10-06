# blessed-cli

A CLI to create / scaffold [blessed]() apps with conventional folder structure and project setup.

## Install 

```
npm install -g blessed-cli
```

## Usage

### Create a new blessed CLI project
```
blessed new <project-name>
```

Example:
```
blessed new my-awesome-cli
```

### Create a new page in the CLI
```
cd my-awesome-cli
blessed page <page-name>
```

For example, if you want to create a page named `home`
```
blessed page home
```

You can also use the alias `p` for creating pages
```
blessed p home
```

### Create a new blessed widget inside the project
```
blessed widget <widget-name>
```
By default, this will create a [Box]() widget.
You can also pass the `--type` option to specify the type of the widget.

```
blessed widget <widget-name> --type list
```

You can also use the alias `w` to create a widget
```
blessed w hello-world --type list
```

## Help
```
blessed <command> <params> <options>

Commands:
  blessed new [project-name]    Create a new blessed project
  blessed page [page-name]      Create a new page component         [aliases: p]
  blessed widget [widget-name]  Create a new blessed widget         [aliases: w]

Options:
      --version  Show version number                                   [boolean]
      --help     Show help                                             [boolean]
  -d, --dry-run  Dry Run: Verify the command without executing         [boolean]

For more information, see https://github.com/terminal-junkies/blessed-cli

```


