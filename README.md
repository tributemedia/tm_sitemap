# Tribute Media Sitemap

## Summary

This feature generates a view that provides a sitemap for a Drupal 7 site. After encountering several issues with our previous sitemap solution, this module was necessary to reliably have a sitemap available.

## Installation

To install, simply upload this feature to your modules folder. Make sure you have the [Views Data Export](https://www.drupal.org/project/views_data_export) module, as it is a dependency for this feature.

## FAQ

###I have installed the module but when I go to see the sitemap I get an error saying that the XML declaration cannot be on line two?

This problem is caused by a closing PHP tag in your template.php file, or in one of your modules (more likely it is in the template.php file). Remove the closing PHP tag and any new lines at the end of the file. Then clear your cache, and you should be good to go.