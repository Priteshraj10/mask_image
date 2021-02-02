# Masking

![Completion Progress Badge](https://img.shields.io/endpoint?url=https%3A%2F%2Fcomma-pencil-completion-badge.cc.workers.dev%2Fbadge.json)

[![HitCount](http://hits.dwyl.com/Priteshraj10/https://githubcom/Priteshraj10/mask_image.svg)](http://hits.dwyl.com/Priteshraj10/https://githubcom/Priteshraj10/mask_image)

![Alt](sample.jpg "First image from the dataset")

Run <pre>./viewer.py</pre> to see them with segement overlay.

## Directories

<pre>
 images/  -- The PNG image files
 masks/ -- PNG segmentation masks (update these!)
 o/p/  -- The outputs in probability from our internal segnet (unreleased, too big)
</pre>

## Categories

<pre>
 1 - #402020 - road (all parts, anywhere nobody would look at you funny for driving)
 2 - #ff0000 - lane markings (don't include non lane markings like turn arrows and crosswalks)
 3 - #808060 - un drivable
 4 - #00ff66 - movable (vehicles and people/animals)
 5 - #cc00ff - my car (and anything inside it, including wires, mounts, etc. No reflections)
</pre>
