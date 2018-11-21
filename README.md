# netuitive.packages.linux.mysql 2.1.0

For detailed information on this package, please refer to the [online documentation](https://help.netuitive.com/Content/Integrations/my_sql.htm).

## Release History

### Version next

* Adjusted build to use metricly-cli for validation
* Changed Queries and Slow_queries metric statistics to max

### Version 2.1.0

* Updated gridstack dashboard layouts

### Version 2.0.0

* Updated package configurations based on:
* Limiting the number of metrics to a core set;
* Fixing an issue where counter metrics were being sent as rates with a type of "gauge";
* Changing the package compatibility setting to be collector-specific.
* Improvements to the computed metrics and policies have been made.
* Miscellaneous bug fixes.

### Version 1.0.1

* Updated configurations for narrower, more accurate, scope.

### Version 1.0.0

* Initial production release of the package for monitoring MySQL resources.  This package works with the MySQL collector of the Linux Agent.
