
#D3ResponsiveGraphs

A modular library of responsive, lightweight, and reusable graphs built with D3js and jQuery (in the next release, jQuery dependency is going to be eliminated). 

##Contents

- [Integration Examples](#integration-examples)
    - [Quick Start](#quick-start)
    - [Examples](#examples)
- [Similar Libraries](#similar-libraries)
- [Graphs](#graphs)
	- [Common Methods](#common-methods)
	- [Common Options](#common-options)
	- [Common Data Structure](#common-data-structure)
	- [D3StackedBar](#d3stackedbar)
		- [Usage](#usage)
		- [Specific Options](#specific-options)
	- [D3LineChart](#d3linechart)
	 	- [Usage](#usage-1)
		- [Specific Options](#specific-options-1)
	- [D3DonutChart](#d3donutchart)
	 	- [Usage](#usage-2)
		- [Specific Options](#specific-options-2)
- [Changelog](#changelog)

## Integration Examples

### Quick Start
Following is a quick example how to create stacked bar chart.

HTML:
```html
<div id="stackedbar"></div>
```
Javascript:
```js
var stackedbar = new D3StackedBar({ 
	container: "#stackedbar"
});
stackedbar.show();
```

