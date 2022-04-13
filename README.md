Drupal 8 Module Development Course

Based on ACQUIA's Youtube [Drupal 8 Module Development Course][(https://www.youtube.com/playlist?list=PLpVC00PAQQxG0sW9YOueVgouRp4aj1bng](https://www.youtube.com/playlist?list=PLpVC00PAQQxHi-llE9Z8-Q747NYWpsq6t))

Remarks:

System uuid for configuration import can be obtained from the data/sites/default/config/system.site.yml Before importing configuration into you local machine use to set the correct uuid on your installation:

vendor/bin/drush config-set "system.site" uuid [uuid]
As an alternative you can also load the provided sql dump (data/drupal-site-building-dump.sql)

A setting.php is also provided on the `data` folder, you can use as a reference (or even just copy it to your installation if you don't run the standard drupal install process)

Materials for the course in the `data/Course files` folder.