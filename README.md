# To reproduce

ddev drush site:install minimal --account-name=admin --account-pass=admin -y
ddev drush cset system.site uuid 1463ec05-e4f4-457c-8f9a-e3c3cf2376b4 -y
ddev drush cr
ddev drush cim -y


