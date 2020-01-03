---
title: jQuery Tree Widget
author: Valerio Galano
type: page
date: 2013-06-04T18:25:57+00:00
dsq_thread_id:
  - 1407539232
catcheverest-sidebarlayout:
  - default
slide_template:
  - default
looks_layout:
  - 2cols_side
trx_addons_post_views_count:
  - 352

---
## Overview

daredevel&#8217;s jQuery Tree is a jQuery UI widget that you can use to add advanced features to an html tree built using nested unordered lists.

It&#8217;s designed to be fast, lightweight, simple to deploy and setup and highly configurable.

  * [Live demo][1]
  * [Issue tracker][2]
  * [Download][3]
  * [Source code][4]<header> 

## Documentation {#documentationindex}</header> 

<div class="quick-nav-section" style="float: left; width: 33%;">
  <h3>
    Options
  </h3>
  
  <p>
    <a href="#optionscheckbox">checkbox</a><br /> <a href="#optionscollapseduration">collapseDuration</a><br /> <a href="#optionscollapseeffect">collapseEffect</a><br /> <a href="#optionscollapseuiicon">collapseUiIcon</a><br /> <a href="#optionscollapsible">collapsible</a><br /> <a href="#optionsdnd">dnd</a><br /> <a href="#optionsexpandduration">expandDuration</a><br /> <a href="#optionsexpandeffect">expandEffect</a><br /> <a href="#optionsexpanduiicon">expandUiIcon</a><br /> <a href="#optionsleafuiicon">leafUiIcon</a><br /> <a href="#optionsselectable">selectable</a><br /> <a href="#optionsselectuiclass">selectUiClass</a>
  </p>
</div>

<div class="quick-nav-section" style="float: left; width: 33%;">
  <h3>
    Methods
  </h3>
  
  <p>
    <a href="#methodsaddnode">addNode</a><br /> <a href="#methodscheck">check</a><br /> <a href="#methodscheckall">checkAll</a><br /> <a href="#methodscollapse">collapse</a><br /> <a href="#methodscollapseall">collapseAll</a><br /> <a href="#methodsdeselect">deselect</a><br /> <a href="#methodsdestroy">destroy</a><br /> <a href="#methodsexpand">expand</a><br /> <a href="#methodexpandall">expandAll</a><br /> <a href="#methodsisroot">isRoot</a><br /> <a href="#methodsmovenode">moveNode</a><br /> <a href="#methodsoption">option</a><br /> <a href="#methodsparentnode">parentNode</a><br /> <a href="#methodsremovenode">removeNode</a><br /> <a href="#methodsselect">select</a><br /> <a href="#methodsselected">selected</a><br /> <a href="#methodsuncheck">uncheck</a><br /> <a href="#methodsuncheckall">uncheckAll</a>
  </p>
</div>

<div class="quick-nav-section" style="float: left; width: 33%;">
  <h3>
    Events
  </h3>
  
  <p>
    <a href="/jquery-tree-widget/#eventsdeselect">deselect</a><br /> &#8230;
  </p>
</div>

<div style="display: block; clear: left;">
</div><section> 

### Options

### checkbox {#optionscheckbox}

<div>
  Type: Boolean
</div>

<div>
  default: true
</div>

Defines if tree nodes will have a checkbox field.

<p style="text-align: right;">
  <a href="#documentationindex">Documentation index</a>
</p>

* * *

### collapseDuration {#optionscollapseduration}

<div>
  Type: Integer
</div>

<div>
  default: 500
</div>

Defines duration of collapse effect in ms. Works only if collapseEffect is not null.

<p style="text-align: right;">
  <a href="#documentationindex">Documentation index</a>
</p>

* * *

### collapseEffect

<div>
  Type: String
</div>

<div>
  default: &#8216;blind&#8217;
</div>

Defines the effect used for collapse node.

<p style="text-align: right;">
  <a href="#documentationindex">Documentation index</a>
</p>

* * *

### collapseUiIcon {#optionsccollapseuiicon}

<div>
  Type: String
</div>

<div>
  default: &#8216;ui-icon-triangle-1-e&#8217;
</div>

Defines jQueryUI icon class used for collapse anchor.

<p style="text-align: right;">
  <a href="#documentationindex">Documentation index</a>
</p>

* * *

### collapsible {#optionscollapsible}

<div>
  Type: Boolean
</div>

<div>
  default: true
</div>

Define if tree nodes can be collapsed.

<p style="text-align: right;">
  <a href="#documentationindex">Documentation index</a>
</p>

* * *

### dnd {#optionsdnd}

<div>
  Type: Boolean
</div>

<div>
  default: true
</div>

Defines if tree has drag and drop feature active.

<p style="text-align: right;">
  <a href="#documentationindex">Documentation index</a>
</p>

* * *

#### expandDuration {#optionsexpandduration}

<div>
  Type: Integer
</div>

<div>
  default: 500
</div>

Defines duration of expand effect in ms. Works only if expandEffect is not null.

<p style="text-align: right;">
  <a href="#documentationindex">Documentation index</a>
</p>

* * *

#### expandEffect {#optionsexpandeffect}

<div>
  Type: String
</div>

<div>
  default: &#8216;blind&#8217;
</div>

Defines the effect used for expand node.

<p style="text-align: right;">
  <a href="#documentationindex">Documentation index</a>
</p>

* * *

#### expandUiIcon {#optionsexpanduiicon}

<div>
  Type: String
</div>

<div>
  default: &#8216;ui-icon-triangle-1-se&#8217;
</div>

Defines jQueryUI icon class used for expand anchor.

<p style="text-align: right;">
  <a href="#documentationindex">Documentation index</a>
</p>

* * *

#### leafUiIcon {#optionsleafuiicon}

<div>
  Type: String
</div>

<div>
  default: &#8221;
</div>

Defines jQueryUI icon class used for leaf anchor.

<p style="text-align: right;">
  <a href="#documentationindex">Documentation index</a>
</p>

* * *

#### selectable {#optionsselectable}

<div>
  Type: Boolean
</div>

<div>
  default: true
</div>

Defines if tree nodes are selectable.

<p style="text-align: right;">
  <a href="#documentationindex">Documentation index</a>
</p>

* * *

#### selectUiClass {#optionsselectuiclass}

<div>
  Type: String
</div>

<div>
  default: &#8216;ui-state-active&#8217;
</div>

Defines jQueryUI class used for selected labels.

<p style="text-align: right;">
  <a href="#documentationindex">Documentation index</a>
</p>

* * *</section> <section> 

#### Methods

#### addNode( attributes, parentLi, position ) {#methodsaddnode}

<div>
  Returns: void
</div>

Add a new node as children of passed one

**attributes**

Type: Object

New node attributes.

**parentLi**

Type: String or Object

Node under which new node will be attached. Object or selector string.

**position**

Type: Integer

Position of the node between brothers (expressed as positive integer).

<p style="text-align: right;">
  <a href="#documentationindex">Documentation index</a>
</p>

* * *

#### check( li ) {#methodscheck}

<div>
  Returns: void
</div>

Check node

**li**

Type: String or Object

Node to check. Object or selector string.

<p style="text-align: right;">
  <a href="#documentationindex">Documentation index</a>
</p>

* * *

#### checkAll( ) {#methodscheckall}

<div>
  Returns: void
</div>

Check all tree elements

<p style="text-align: right;">
  <a href="#documentationindex">Documentation index</a>
</p>

* * *

#### collapse( li, effect, force ) {#methodscollapse}

<div>
  Returns: void
</div>

Collapse node

**li**

Type: String or Object

Node to collapse. Object or selector string.

**effect**

Type: Boolean

Apply effect.

**force**

Type: Boolean

Force to already collapse node.

<p style="text-align: right;">
  <a href="#documentationindex">Documentation index</a>
</p>

* * *

#### collapseAll( ) {#methodscollapseall}

<div>
  Returns: void
</div>

Collapse all nodes of the tree

<p style="text-align: right;">
  <a href="#documentationindex">Documentation index</a>
</p>

* * *

#### deselect( ) {#methodsdeselect}

<div>
  Returns: void
</div>

Deselect selected node

<p style="text-align: right;">
  <a href="#documentationindex">Documentation index</a>
</p>

* * *

#### destroy( ) {#methodsdestroy}

<div>
  Returns: void
</div>

Cleanup DOM elements removing plugin instance

<p style="text-align: right;">
  <a href="#documentationindex">Documentation index</a>
</p>

* * *

#### expand( li, effect, force ) {#methodsexpand}

<div>
  Returns: void
</div>

Expand node

**li**

Type: String or Object

Node to expand. Object or selector string.

**effect**

Type: Boolean

Apply effect.

**force**

Type: Boolean

Force to already expanded node.

<p style="text-align: right;">
  <a href="#documentationindex">Documentation index</a>
</p>

* * *

#### expandAll( ) {#methodsexpandall}

<div>
  Returns: void
</div>

Expand all nodes of the tree

<p style="text-align: right;">
  <a href="#documentationindex">Documentation index</a>
</p>

* * *

#### isRoot( li ) {#methodsisroot}

<div>
  Returns: Object
</div>

Check if passed node is a root

**li**

Type: String or Object

Node to check if is root. Object or selector string.

<p style="text-align: right;">
  <a href="#documentationindex">Documentation index</a>
</p>

* * *

#### moveNode( li, parentLi, position ) {#methodsmovenode}

<div>
  Returns: void
</div>

Move a node under new parent

**li**

Type: String or Object

Node to move. Object or selector string.

**parentLi**

Type: String or Object

Node under which node will be attached. Object or selector string.

**position**

Type: Integer

Position of the node between brothers (expressed as positive integer).

<p style="text-align: right;">
  <a href="#documentationindex">Documentation index</a>
</p>

* * *

#### option( optionName ) {#methodsoption}

<div>
  Returns: Object
</div>

Gets the value currently associated with the specified optionName.

**optionName**

Type: String

The name of the option to get.

<p style="text-align: right;">
  <a href="#documentationindex">Documentation index</a>
</p>

* * *

#### option( ) {#methodsoption}

<div>
  Returns: PlainObject
</div>

Gets an object containing key/value pairs representing the current datepicker options hash.

<p style="text-align: right;">
  <a href="#documentationindex">Documentation index</a>
</p>

* * *

#### option( optionName, value ) {#methodsoption}

<div>
  Returns: void
</div>

Sets the value of the datepicker option associated with the specified optionName.

**optionName**

Type: String

The name of the option to set.

**value**

Type: Object

A value to set for the option.

<p style="text-align: right;">
  <a href="#documentationindex">Documentation index</a>
</p>

* * *

#### option( options ) {#methodsoption}

<div>
  Returns: void
</div>

Sets one or more options for the datepicker.

**options**

Type: Object

A map of option-value pairs to set.

##### Code examples:

> `$( ".selector" ).tree( "option", { collapseDuration: 1000 } );`

<p style="text-align: right;">
  <a href="#documentationindex">Documentation index</a>
</p>

* * *

#### parentNode( li ) {#methodsparentnode}

<div>
  Returns: Object
</div>

Return parent li of the passed li

**li**

Type: String or Object

Node you want to get parent of. Object or selector string.

<p style="text-align: right;">
  <a href="#documentationindex">Documentation index</a>
</p>

* * *

#### removeNode( li ) {#methodsremovenode}

<div>
  Returns: void
</div>

Remove a node from tree (node is not actually delete, but still in memory)

**li**

Type: String or Object

Node to remove. Object or selector string.

<p style="text-align: right;">
  <a href="#documentationindex">Documentation index</a>
</p>

* * *

#### select( li ) {#methodsselect}

<div>
  Returns: void
</div>

Return a node

**li**

Type: String or Object

Node to select. Object or selector string.

<p style="text-align: right;">
  <a href="#documentationindex">Documentation index</a>
</p>

* * *

#### selected( ) {#methodsselected}

<div>
  Returns: Object
</div>

Return selected node

<p style="text-align: right;">
  <a href="#documentationindex">Documentation index</a>
</p>

* * *

#### uncheck( li ) {#methodsuncheckall}

<div>
  Returns: void
</div>

Uncheck node

**li**

Type: String or Object

Node to uncheck. Object or selector string.

<p style="text-align: right;">
  <a href="#documentationindex">Documentation index</a>
</p>

* * *

#### uncheckAll( ) {#methodsuncheckall}

<div>
  Returns: void
</div>

Uncheck all tree elements

<p style="text-align: right;">
  <a href="#documentationindex">Documentation index</a>
</p>

* * *</section> <section> <header>Events</header> 

#### add( event, element )

#### move( event, element )

#### remove( event, element )

#### collapse( event, element )

#### expand( event, element )

#### deselect( event, element ) {#eventsdeselect}

<div>
  Type: treedeselect
</div>

Defines function to handle deselect event

**event**

**element**

<p style="text-align: right;">
  <a href="#documentationindex">Documentation index</a>
</p>

* * *

#### drop( event, element )

<div>
  Type: treedrop
</div>

Defines function to handle drop event

**event**

**element**

<p style="text-align: right;">
  <a href="#documentationindex">Documentation index</a>
</p>

* * *

#### select( event, element )

<div>
  Type: treeselect
</div>

Defines function to handle select event

**event**

**element**

<p style="text-align: right;">
  <a href="#documentationindex">Documentation index</a>
</p>

* * *</section>

 [1]: http://htmlpreview.github.io/?https://github.com/daredevel/jquery-tree/blob/master/index.html "Live demo"
 [2]: https://github.com/daredevel/jquery-tree/issues
 [3]: https://github.com/daredevel/jquery-tree/archive/master.zip
 [4]: https://github.com/daredevel/jquery-tree