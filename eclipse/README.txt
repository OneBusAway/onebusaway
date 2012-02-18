Eclipse code style instructions:

== Configure Eclipse Environment==

  All relative paths are relative to the source project root.

---------- Code style/formatting ----------

Project->Properties->Java Code Style->Formatter->Import...
  eclipse/code-style/org.onebusaway-format.xml

----------- Import organization -----------

Project->Properties->Java Code Style->Organize Imports->Import...
  eclipse/code-style/org.onebusaway.importorder
  
------------ XML Formatting ---------------

Unfortunately, you have to manually configure XML formatting under
XML->XML Files->Editor:

Line width: 120
Indent using spaces
Indentation size: 2

See the xml-formatting.png in CodeStyle for an example.
