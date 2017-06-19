# Mavenized Swing NetBeans RCP

This is a small maven project that bundles together some jars of the NetBeans Rich Client Platform, so that it's easier to use them in plain Swing applications.

## License

For the NetBeans license [see this page](https://netbeans.org/about/legal/product-licences.html)

## Use

1. Select a NetBeans Platform version

[see this page](http://bits.netbeans.org/nexus/content/groups/netbeans/org/netbeans/api/org-openide-util/) for a list of versions.

2. Clone this repository, edit the `pom.xm` file and set the `version.netbeans` property to the desired value.

3. Perform a `mvn clean install`

4. Use the project in your Swing app:

```xml
		<dependency>
			<groupId>net.vieiro</groupId>
			<artifactId>mvnnbp</artifactId>
			<version>0.0.1-SNAPSHOT</version>
		</dependency>```

## Documentation

See [NetBeans Platform on standalone Swing applications](https://vieiro.net/apuntes/swingnbrcp/) for examples.


