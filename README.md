# Drupal 9 with Gin Admin Theme Demo

A Drupal 9 Gin Future Admin UI Demo.

![Gin Admin UI](https://www.drupal.org/files/project-images/Gin_form_display.png)

## Prerequisites

### Get Lando
Install Lando: https://docs.lando.dev/basics/installation.html

---

## Installation

### Clone repo
Clone the repo
```
git clone git@github.com:saschaeggi/drupal9-gin.git && cd drupal9-gin
```

### Let's build the app
```
lando start
```

### You're ready to go
https://drupal9.lndo.site/

---

## Commands

### Start containers
```
lando start
```

### Stop containers
```
lando stop
```

#### Poweroff Lando
```
lando poweroff
```

### SSH into container
```
lando ssh
```


### Drush
Make sure you're in the frontend folder (`cd web`)

```
lando drush COMAMND
```

### Composer
Make sure you're in the frontend folder (`cd web`)

```
lando composer COMMAND
```

---

## Drupal

https://drupal9.lndo.site/

```
username: admin
password: drupal
```
