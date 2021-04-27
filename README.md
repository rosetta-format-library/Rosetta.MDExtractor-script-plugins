- Rosetta.MDExtractor-script-plugins
- updated to v1.1
- original v1.0 versions now part of v1.0 release
- both ExifTool and MediaInfo had updated MediaInfoMDExtractorPlugin.jar\PLUGIN-INF\properties.xml and MediaInfoMDExtractorPlugin.jar\PLUGIN-INF\transformer.xsl so they work with latest versions of the tool
- 'metadata_ExifToolMDExtractorPlugin.xml' and 'metadata_MediaInfoMDExtractorPlugin.xml' file in \PLUGIN-INF\ inside the plugin updated (element <pl:version> value is 1.1), so the plugins actually get deployed over the old version should you have it in your instance of Rosetta

