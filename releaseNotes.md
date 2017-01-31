# ************************* #
# EVT 1.1.1 - RELEASE NOTES # 
# ************************* #

# Please note that for the first there is an incompatibility with regard to a previous version of EVT: read carefully the first item, and check the manual!

# Changed the starting point of the transformation which is now based on <text> (also when using a <group> element): this is **the most important difference** compared to EVT 1.0, in fact note that the old method based on <div> does not work anymore, so please make sure to read the EVT 1.1 manual on this point;

# Added support for image formats other than JPEG;

# Added German language support thanks to Christian Schuster from [Transylvania Digital Humanities Centre] (http://centre.ubbcluj.ro/digihubb/) who actually translated the English localization file;

# Added support for list of organizations (<listOrg>) and named entities <org>s;

# Added a template to rend italicized <title>s in <note>s;

# Added files for custom XSLT templates (evt_builder-custom-templates.xsl) and CSS rules (evt_builder-custom-styles.css), check section 3 of the manual;

# Added a distinction between critical <note>s and comment <note>s;

# Renamed evt_builder-miscellaneous.xsl into evt_builder-general.xsl;

# Added initial support for original content encoded into a <front>;

# Many bug fixes!