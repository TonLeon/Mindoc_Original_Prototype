---
layout: default
title: Photographs
number: 007
---

# Photographs

Throughout this edition, we have included supplementary images that show the work completed in Anna Coleman Ladd's studio.  These stills and photographs were also provided to SourceLab by the Otis Historical Archives, which also has a large collection of papers concerning Anna Coleman Ladd herself.
Full titles and correction citation information for each item are included within the photographs.  Simply click on the ‘Details’ button within each frame, and look in the field marked "description."
 
In addition to the photographs used throughout our edition, we are able to provide the following images for public use, thanks to the Otis Historical Archives:
 
 
Patient Shown Without a Mask 
 
This Patient Would Not Go Out Until Mrs. Ladd Covered His Disfigurement with a Mask
 
Different Stages of Mutilation

Collection of Plaster Face Casts

Cast Taken from Mutilated Face

Mutilated French Soldier with Mask

Mutilated French Soldier Without Mask

Mutilated French Soldier Without Mask (Side View)

{% assign media = site.mindoc_media | sort: "order" | where_exp: "item", "item.page == 'photographs'" | where_exp: "item", "item.media_type == 'image'" %} 
{% include media.html pages=media %}


