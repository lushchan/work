## wordpressinstaller
WordPress autoinstaller

## Run: 

Just run this script from root directory of domain

## params:
`-m - for manual mode`

`-f - automatic mode`

#
## Manual mode(-m):
Manual input database credentials
## Automatic mode(-f):
Auto create database, user and password from current path
example:
`if path /home/ftpaccess/domain.com/www/
database name: wpdomaincom
database user: wpudomaincom
password: 'generated by pwgen'`

## Notes: 

pwgen required(`apt install pwgen \\ yum install pwgen`)

File structure mus be like this `/home/username/domain.com/`

Document root must be like `www/html/public_html`

Database user name skiped or replaced specific characters like `"-","."`

MySQL root password must be saved in `~/.my.cnf` [WHAT???](https://stackoverflow.com/questions/16299603/mysql-utilities-my-cnf-option-file)
