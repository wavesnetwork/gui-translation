# Internationalization support for CASUS

# The WAVES Project

The WAVES project combines skill sets of both academic and enterprise partners to make Scenario-based learning (SBL) more accessible for a wide range of professions.  SBL techniques are widely recognised as a key tool in the educational toolkit, for safe training in competency and decision-making.

[http://wavesnetwork.eu](http://wavesnetwork.eu)

# Online demo

More information about how to request a demo:

[WAVES Internationalisation support for CASUS Demo](https://www.instruct.eu/en/)

Polish translation of the GUI is ready and part of the CASUS web site [http://krakow.casus.net](http://krakow.casus.net)

# What's in the box

The [CASUS Learning System](https://www.instruct.eu/en/) has at this moment about 2.400 labels and text blocks per language. In the past CASUS focused on
<ul>
	<li>English and</li>
	<li>German</li>
</ul>

As part of WAVES project the following languages were added
<ul>
	<li>Polish</li>
</ul>

We classified the languages in the following way
<ul>
	<li>Core languages, which are maintained by the CASUS team</li>
	<li>Additional languages maintained with support from partners</li>
</ul>

The language specific resources are JAVA property files that consist of key and value pairs; the key is a defined label used in the internationalized templates, the value is the actual translation. Direct work on these property files is possible but not really useful for non-technical persons. The objective of this task was to experiment with a tool, providing a easy to use interface to translate such JAVA property files.

# How to contribute
You can contribute through pull requests. You can either:
1. Improve existing translations
2. Suggest new translations

You can use the free GUI-translation tool from Martin Adler, also part of the WAVES project.
The tool sources are available in an open bitbucket repository [https://bitbucket.org/gulpipvt/i18properties](https://bitbucket.org/gulpipvt/i18properties).

Main configuration can be done by setting the directory of the property files, access control can be achieved by using standard JAVA webapp access methods, so can also be integrated into other systems.


# License 
WAVES Internationalization support for CASUS is licensed under the MIT Open Source license. For more information, see the LICENSE file in this repository.