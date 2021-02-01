# Masking

![Completion Progress Badge](https://img.shields.io/endpoint?url=https%3A%2F%2Fcomma-pencil-completion-badge.cc.workers.dev%2Fbadge.json)


![Alt](sample.jpg "First image from the dataset")

Run <pre>./viewer.py</pre> to see them with segnet overlay.

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
 3 - #808060 - undrivable
 4 - #00ff66 - movable (vehicles and people/animals)
 5 - #cc00ff - my car (and anything inside it, including wires, mounts, etc. No reflections)
</pre>

### Tutorial
<a href="https://youtube.com/watch?v=RxqG15zOmCk" title="img-labeler Tutorial Video" rel="noopener noreferer"><img src="https://i.ytimg.com/vi/RxqG15zOmCk/maxresdefault.jpg" width="480px"></a>
