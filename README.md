# Digital Garden

A CLI tool for the creation and maintenance of Digital Gardens.

## Commands

## Setting the garden path

```shell
GARDEN_PATH=~/github/my-digital-garden garden write
garden -p ~/github/my-digital-garden write
garden --garden_path ~/github/my-digital-garden write
```

### write

Write will open a new file to write in our Digital Garden. Since we don't necessarily know what we want to title what we're writing, we'll leave the title as optional and ask the user for it later if they don't provide it upfront.

```shell
garden write
garden write -t "Some Title"
```