# ChangeLog

## Unreleased

## 2.16.1 - (February 2, 2021)

* Changed
  * Fixed linter issues.
  * Fixed Y-axis range bug in reflow. 

## 2.16.0 - (December 16, 2020)

* Changed
  * For consistency replaced `document` in all draw helpers with `graph.legendSVG` for better control.
  * For consistency updated reflow in Graph and Gantt constructs to update the eventlines.
  * Added code to handle null/undefined/blank in paired result graph during both initial load and reflow.
  * Updated `packages/carbon-graphs/README.md` so that it has more essential information about Carbon.
  * Added array handling for loadContent on Construct based graphs.
  * Throw an error when null/undefined/blank is passed as y value.
  * Connecting line does not go away for paired results when toggled off in Internet Explorer.

## 2.15.0 - (November 24, 2020)

* Changed
  * Added a condition to check if graphContainer is present and then resize the graph.
  * Migrated to the terra-graphs mono-rep.
