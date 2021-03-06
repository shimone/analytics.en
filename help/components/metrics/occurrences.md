---
title: Occurrences
description: The number of hits that a variable was set or persisted.
---

# Occurrences

The 'Occurrences' metric shows the number of hits where a given dimension was set or persisted. When you drag a dimension in Workspace to a blank canvas, Adobe automatically applies this metric to the project.

## How this metric is calculated

Out of all hits in a report suite, include hits where a dimension item is defined or persisted. Some dimensions, such as [eVars](../dimensions/evar.md), persist beyond the hit they are set on. Metrics like [Page views](page-views.md) and [Occurrences](occurrences.md) count both initial and persisted values. This metric does not count persisted values.

## Compare to similar metrics

* **Occurrences vs. [Instances](instances.md)**: Occurrences count hits where a dimension item was set or persisted. Instances do not include hits where a dimension item persists.
* **Occurrences vs. [Page views](page-views.md)**: Occurrences include all hit types, including page view tracking calls ([`t()`](/help/implement/vars/functions/t-method.md)) and link tracking calls ([`tl()`](/help/implement/vars/functions/tl-method.md)). The page views metric only includes page view tracking calls, and excludes link tracking calls.