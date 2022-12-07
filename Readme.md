# Please config maven setting file for idea


# snapshot
- mvn deploy -s ./settings.xml

# release
- mvn release:prepare
- mvn release:perform -s ./settings.xml 