# EducaAndOS-plus

A theme for eggs, let you to save your time.

A theme consist in a structures insieme di files and directories, YAML language is the used most.

* applications
* artwork
* calamares
* livecd

## applications
Just a desktop link, will be copied to ```/usr/share/applications/``` and on the Desktop.

## artwork
The icon for your desktop link

## calamares
Contain the calamares customizations and it's by far the most important.

### branding

### modules
* locale.yml
* partitions.yml
* users.yml

## livecd
The apparence of your live.

## usage:

```
sudo eggs produce --fast --theme ../path/to/theme
```
## example

Clone this theme:

```
git clone https://github.com/pieroproietti/educaandos-plus```
```

And produce your iso:

```
sudo eggs produce --fast  --theme ../educaandos-pluc
```


