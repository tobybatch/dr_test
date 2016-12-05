QUICKSTART
==========

    drush dl drupal-7.x
    cd drupal-7.x-dev/
    drush si --db-su=root --db-su-pw=XXXXXXX --db-url=mysql://dr_test_01:dr_test_01@localhost/dr_test_01 --account-mail=tobias@neontribe.co.uk --account-name=superadmin --account-pass=XXXXXXX
    cd sites/
    git clone --recursive git@github.com:tobybatch/dr_test.git
    cp -r default/{files,settings.php} dr_test
    mv default default.old
    mv dr_test default
