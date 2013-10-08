Java Web Framework (JWF) Implementations
========================================

This is the set of all the completed (or started) Java Web Framework
demonstration implementations. Each shows a simple webapp that
allows the user to enter standard "signup" data, and puts it
into a database, and lets you list the database.

This work was started as part of my M.Sc. work but has been continued
(very sporadically) as a sort of hobby.  There are 100 Java Web
Frameworks and about a dozen implementations here, so you can see
that the coverage is very sporadic at best.

Each jwf.* subdirectory is an Eclipse Project with one of the impls;
the name should make it clear which framework is demonstrated.

Do not expect consistency about the batch build system; some use Ant,
some use Maven, maybe by the time you use this, some will use Gradle.
Some probably have no build file.

The jwf-datamodel is common code that some of the impls use, or should.
Its Person class provides the quasi-canonical list of fields for
the impls that don't use this standard Entity object.

No claim is made that these are "best practices" versions;
some are very old and could be updated!

Please contribute your own favorites, if you care.

Impls I'd like to see, or do:

	Seam2
	Grails (replacing the "Groovy" one)