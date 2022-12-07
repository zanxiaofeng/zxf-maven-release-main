# Maven setting
- For maven from Idea, Please config idea maven setting from idea menu File/Settings.
- For maven from command line, please use [mvn -s ./settings.xml]

# snapshot
- mvn deploy -s ./settings.xml

# release
- mvn release:prepare
- mvn release:perform -s ./settings.xml 