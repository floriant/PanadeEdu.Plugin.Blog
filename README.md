TYPO3 Neos Blog Plugin
======================

This plugin provides a node-based plugin for TYPO3 Neos websites.

Note: this package is still experimental and may change heavily in the near future.

Quick start
-----------
* include the Plugin's route definitions to your `Routes.yaml` file, just like

```yaml
-
  name: 'PanadeEduBlogPlugin'
  uriPattern: '<PanadeEduPluginSubroutes>'
  subRoutes:
    PanadeEduBlogPlugin:
      package: PanadeEdu.Plugin.Blog
```

* include the plugin's TypoScript definitions to your own one's (located in, for example, `Packages/Sites/Your.Site/Resources/Private/TypoScripts/Library/ContentElements.ts2`, with:

```
include: resource://PanadeEdu.Plugin.Blog/Private/TypoScripts/Library/NodeTypes.ts2
```

* add the plugin content element "Blog Post Overview" to the position of your choice.

* NOTE:

This is a Custom fork of Robert Lemkes origin Plugin.Blog the mess around with Neos. 