---
layout: default
title: Hidden Berkeley
---

# Locations in UC Berkeley

Hi there, you must be a new student! Here is a beginner's guide to important places and services in Berkeley. Check each resource's official webpage for current access details.

<!-- Edit the heading and introduction above. The supplied loop below displays each row of the CSV. -->
{% for resource in site.data.locations %}

### {{ resource.name | escape }}

**Category:** {{ resource.category | escape }}  
**Area:** {{ resource.area | escape }}  
**Access note:** {{ resource.access_note | escape }}  
<a href="{{ resource.source_url | escape }}">Official source</a>

{% endfor %}

---

The entries come from this project's CSV. Confirm current details using the official links.
