# Covering

## Overview

Spatial objects can be covered with spatial regions (e.g. bounding boxes):

```@docs
cover(::Any, ::AbstractCoverer)
```

Other utility functions are available, which are implemented with the general
`cover` function:

```@docs
boundbox
```

## Example

```@example
using GeoStats # hide

R = boundbox(RegularGrid(50, 80))

lowerleft(R), upperright(R)
```

## Methods

```@docs
RectangleCoverer
```
