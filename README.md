# CLI-GENERATE

Script for generating code by template

## INSTALLATION

```
npm install -g cli-generate
```

## DESCRIPTION

This script needs for generating a lot of files by template. You need define source and target paths and names of models for generating. Script replaces 'template-model' in your files and in all paths to your model name, also you can set different all modification of 'template-model' and can use plural in names.

## USAGE

```
$ generate --help

generate

  Generate files by templates

Usage:

  generate [options...] <source> <target> [models...]

Options:

  -h, --help              Show help
  -V, --version           Show version.
  -c, --cwd [string=null]
```