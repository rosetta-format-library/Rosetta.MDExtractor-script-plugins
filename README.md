## Rosetta.MDExtractor-script-plugins
*  ExifToolMDExtractorPlugin - v1.2 
*  MediaInfoMDExtractorPlugin - v1.1

- both ExifTool and MediaInfo had updated MediaInfoMDExtractorPlugin.jar\PLUGIN-INF\properties.xml and MediaInfoMDExtractorPlugin.jar\PLUGIN-INF\transformer.xsl so they work with latest versions of the tool
- 'metadata_ExifToolMDExtractorPlugin.xml' and 'metadata_MediaInfoMDExtractorPlugin.xml' file in \PLUGIN-INF\ inside the plugin updated (element <pl:version> value), so the plugins actually get deployed over the old version you have in your instance of Rosetta

[**How to add (not bundled) MD extractor plugins to Rosetta**](https://share.getty.edu/display/RUG/How+to+add+%28not+bundled%29+MD+extractor+plugins+to+Rosetta) - guideline for Rosetta users on WG Wiki.
