## All Projects

This is an OpenAtrium feature designed to add another field to the 
_Project_ content type used in OpenAtrium called _Funding Source_.

This module uses the [Features](http://drupal.org/project/features) module that ships with OpenAtrium. It is also heavily dependant on OpenAtrium, so it most likely will not work very well without it. It ties together with the _Project_ content type.

After installation, a new field is added to the _Project_ content type allowing the user to enter a _Funding Source_ for the project.

This module alse creates a new block, called _All Projects_ and adds it to the header region. It is enabled by deafault and only shows on the front page, meaning it gets out of the way and leaves the default user interface mostly intact for project management. This allows quick access to the projec-overview page that is a view listing projects and their funding sources.The view is sortable by project name or funding source and also includes a pager.

### Installation

1. Install as you would any other module by copying the entire project_discussion folder to sites>all>modules or profiles>openatrium>modules>contrib
2. After the files are copied, visit admin>build>features and under the features heading, enable _All Projects_

### License
This module integrates heavily with [OpenAtrium](http://openatrium.com) which itself uses [Drupal](http://drupal.org). So it is licensed under the [GNU GPL](http://www.gnu.org/copyleft/gpl.html).

### Development

This module was created for use by the United States Federal Government by [RadiantBlue Technologies](http://radiantblue.com) for the [Department of Defense](http://defense.gov) and the [National Geospatial Intelligence Agency](http://nga.mil).

### Enhancements

There may be some enhancements added in a separate branch depending on what the client wants, so watch this space for updates.