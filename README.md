# EducaAndOS-plus

A theme for eggs, let you to save your time.

An eggs theme is simply an organized set of files and directories, YAML being the most widely used.

EducaAndOS is the first example of an external eggs theme available, previous themes: neon, ufficiozero, telos and waydroid will be via, via moved out of eggs itself and updated to the present configurations.

We currently have the following directories:
* applications
* artwork
* calamares
* livecd

## applications
Just a desktop link, will be copied to ```/usr/share/applications/``` and on the Desktop.

## artwork
The icon for your desktop link, will be copied on ```/usr/share/icons/```

## calamares
Contain the calamares customizations and it's by far the most important.

### branding

### modules
* locale.yml
* partitions.yml
* users.yml

### locale.yml
Not used yet.

### partitions.yml
Not used yet.

### users.yml
In EducaAndOS to ensure administration capability for our user, we need a groups configuration specified in users.yml. Note: If it is not specified as thema educaandos, the configuration of groups in which the live user and the installed system user will be part, will not have the possibility of administration.


## livecd
Take cure of the apparence of your live.

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
sudo eggs produce --fast  --theme ../educaandos-plus
```


