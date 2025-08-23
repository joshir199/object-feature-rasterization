# object-feature-rasterization



\*\*NOTE\*\*: this is a modified version to support object feature rendering (both forward and backward) from the \[original repository](https://github.com/graphdeco-inria/diff-gaussian-rasterization). 



```python

rendered\_image, radii, rendered\_depth, rendered\_alpha = rasterizer(

&nbsp;   means3D=means3D,

&nbsp;   means2D=means2D,

&nbsp;   shs=shs,

&nbsp;   colors\_precomp=colors\_precomp,

&nbsp;   opacities=opacity,

&nbsp;   scales=scales,

&nbsp;   rotations=rotations,

&nbsp;   cov3D\_precomp=cov3D\_precomp,

)

```





Used as the rasterization engine for the paper "3D Gaussian Splatting for Real-Time Rendering of Radiance Fields". If you can make use of it in your own research, please be so kind to cite us.



<section class="section" id="BibTeX">

&nbsp; <div class="container is-max-desktop content">

&nbsp;   <h2 class="title">BibTeX</h2>

&nbsp;   <pre><code>@Article{kerbl3Dgaussians,

&nbsp;     author       = {Kerbl, Bernhard and Kopanas, Georgios and Leimk{\\"u}hler, Thomas and Drettakis, George},

&nbsp;     title        = {3D Gaussian Splatting for Real-Time Radiance Field Rendering},

&nbsp;     journal      = {ACM Transactions on Graphics},

&nbsp;     number       = {4},

&nbsp;     volume       = {42},

&nbsp;     month        = {July},

&nbsp;     year         = {2023},

&nbsp;     url          = {https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/}

}</code></pre>

&nbsp; </div>

</section>



