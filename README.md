# CLI-TEMPLATE

Script for generating code by template

## INSTALLATION

```
npm install -g cli-template
```

## DESCRIPTION

This script needs for generating a lot of files by template. You need define source and target paths and names of models for generating. Script replaces 'template-model' in your files and in all paths to your model name, also you can set different all modification of 'template-model' and can use plural in names.

## USAGE

```
$ tpl --help

template

  Generate files by templates

Usage:

  tpl [options...] <command> [arguments...] [options...]

Options:

  -h, --help              Show help
  -V, --version           Show version.
  -c, --cwd [string=null]

Commands:

  add <name> <source>
    This command remembers your template in your home directory and requires name and path to source for saving.

  remove <name>
    This command removes your template from your home directory and requires name for removing.

  recovery <name> <target>
    This command recovers code from saved template into folder.

  list 
    This command shows all saved templates.

  generate <name> <target> [models...]
    This command generates code from saved template and requires saved template name and target folder for generating, also you need to define list of model names.

  inline <source> <target> [models...]
    This command generates code inline from source folder and requires path to source folder and target folder for generating, also you need to define list of model names.
```