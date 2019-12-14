# idc-auth-server
nodejs server

config: src/server-config.ts

# Installation 

Database config.mysql 

install database tables run: npm create_tables

Important !!! do not run it with current config it will kill all data in table

email
check documentation npm "nodemailer": "^5.1.1"

config config.email

email templates

"etc/confirm_en.htm"

"etc/reset_en.htm"

templates have {{confirmUrl}} to be replaced at runtime by url provided in config

{{firstName}} placeholder  in reset.htm

//TODO set in config


token config.token

signature generated from web tools 
"etc/private.key"
"etc/public.key"


https://docs.google.com/document/d/1m_CjuG484z0N3Gs-mIUY_ASchddOe8r5WWzjcETROKI/edit





