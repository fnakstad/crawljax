Crawljax Plugins Parent POM
===========================

The parent Maven POM for Crawljax plugins. 

Parent POM
----------
Start out by adding the parent configuration to your pom:

    <parent>
      <groupId>com.crawljax.plugins</groupId>
      <artifactId>plugin</artifactId>
      <version>2.1</version>
    </parent>


The parent POM isn't available in a public Maven repository yet. You need to declare the [Crawljax Maven repository](https://github.com/crawljax/crawljax-mvn-repo) in your POM.


Properties
----------

The pom includes properties that allow various build configurations to be customized. 
For example, to override the default version of crawljax, just set a property:

    <properties>
      <crawljax.version>VERSION</crawljax.version>
    </properties>


Building Plugins
----------------

For more information on how to write a Crawljax plugin see [this page](https://github.com/crawljax/crawljax/wiki/Writing-a-plugin).
