# 3. Use Semantic Elements
Semantic elements are HTML elements which provide a structure and meaning to the content on the webpage. When content is structured, it is easier for assistive technology users including screen reader users to understand content without having to add unnecessary explanations.

## Activity
1. Apply the `<blockquote>` element to all reviews

## Solution
* The `<blockquote>` is applied to all quotes on the page, the `<cite>` element within `<blockquote>` is also applied
```
<blockquote class="text-muted correct">
  These sneakers are just what I needed! they have a mixture of fabrics, and provide fantastic heel support. 
  The underside however, has a hard wearing sole which becomes slippery in the rain.
  <cite class="font-size-xs text-muted">
    Logan Edwards, <time datetime="2019-06-01">01 Jun 2019</time>
  </cite>
</blockquote>
```

## Live Demo
Use Semantic Elements