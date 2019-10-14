```
$ sbt dependencyTree
[info] Loading settings for project global-plugins from idea.sbt,plugins.sbt,metals.sbt ...
[info] Loading global plugins from ~/.sbt/1.0/plugins
[info] Loading settings for project coursier-issue-1405-build from plugins.sbt ...
[info] Loading project definition from ./project
[info] Loading settings for project coursier-issue-1405 from build.sbt ...
[info] Set current project to coursier-issue-1405 (in build file:./)
[info] commons-jelly:commons-jelly:1.0
[info]   +-commons-beanutils:commons-beanutils:1.6
[info]   | +-commons-collections:commons-collections:2.0 (evicted by: 2.1)
[info]   | +-commons-collections:commons-collections:2.1
[info]   | +-commons-logging:commons-logging:1.0 (evicted by: 1.0.3)
[info]   | +-commons-logging:commons-logging:1.0.3
[info]   | 
[info]   +-commons-cli:commons-cli:1.0
[info]   | +-commons-lang:commons-lang:1.0 (evicted by: 2.0)
[info]   | +-commons-lang:commons-lang:2.0
[info]   | +-commons-logging:commons-logging:1.0 (evicted by: 1.0.3)
[info]   | +-commons-logging:commons-logging:1.0.3
[info]   | 
[info]   +-commons-collections:commons-collections:2.1
[info]   +-commons-discovery:commons-discovery:0.2-dev
[info]   | +-commons-logging:commons-logging:1.0.3
[info]   | 
[info]   +-commons-discovery:commons-discovery:20030211.213356 (evicted by: 0.2-dev)
[info]   +-commons-jexl:commons-jexl:1.0
[info]   +-commons-lang:commons-lang:2.0
[info]   +-commons-logging:commons-logging:1.0.3
[info]   +-forehead:forehead:1.0-beta-5
[info]   +-jaxen:jaxen:1.1-beta-4
[info]   | +-xerces:xercesImpl:2.6.2
[info]   | +-xom:xom:1.0b3
[info]   |   +-org.ccil.cowan.tagsoup:tagsoup:0.9.7
[info]   |   +-xerces:xercesImpl:2.2.1 (evicted by: 2.6.2)
[info]   |   +-xerces:xercesImpl:2.6.2
[info]   |   
[info]   +-xml-apis:xml-apis:1.0.b2
[info]   
[info] default:coursier-issue-1405_2.12:0.1.0-SNAPSHOT
[success] Total time: 0 s, completed 14 oct. 2019 23:29:55
```
