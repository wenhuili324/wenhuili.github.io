---
title:  "Shear Thinning of Lubricants"
mathjax: true
layout: post
categories: media
---
Shear thinning is a phenomenon where a fluid’s viscosity decreases with increasing shear rate, playing a critical role in many industrial applications. For example, lubricants—typical shear-thinning fluids—reduce friction and wear between moving parts, and their viscosity response under shear is essential for maintaining optimal performance.

Laboratory experiments are typically limited to shear rates below 10⁵ s⁻¹, whereas real-world applications—such as engine oil lubrication—can involve shear rates reaching up to 10¹⁰ s⁻¹. While many rheological models can fit experimental data well within the measured range, their predictions often diverge significantly when extrapolated to higher shear rates. This makes it challenging to develop accurate rheological models that reliably capture shear thinning behavior across a broad spectrum of shear rates.

In this project, we employed non-equilibrium molecular dynamics (NEMD) simulations to investigate the rheological properties of lubricant molecules under high shear rates. NEMD has proven to be a powerful and reliable tool for accurately reproducing the Newtonian viscosities of lubricants. By combining NEMD simulation results with existing experimental data, we evaluated two key categories of rheological models central to the ongoing debate.

The first category includes power-law models, which posit that lubricant molecules align increasingly with the shear direction, thereby reducing intermolecular friction and, consequently, viscosity. The second category involves thermal activation models, which describe shear flow as a stress-biased, thermally activated process. In these models, applied shear stress lowers the energy barrier for molecular movement in the shear direction while raising it in the opposite direction.

We applied machine learning techniques—specifically, dimensionality reduction methods such as Principal Component Analysis (PCA) and t-distributed Stochastic Neighbor Embedding (t-SNE)—to investigate the relationship between molecular orientation and shear rate in greater depth. Our analysis revealed that molecular orientation changes progressively with increasing shear rate at low to medium levels but becomes saturated at medium to high shear rates. Interestingly, fluid viscosity continues to decrease in this higher shear rate regime, which contradicts the assumptions of the power-law model.

To evaluate the validity of thermal activation models, we analyzed molecular rearrangement patterns, which these models identify as the primary mechanism behind shear thinning. Our results show that the observed molecular rearrangements are consistent with the theoretical predictions of the thermal activation model, supporting its relevance in describing rheological behavior at high shear rates.

See our publications:

[Comparing Phenomenological Models of Shear Thinning of Alkanes at Low and High Newtonian Viscosities](https://link.springer.com/article/10.1007/s11249-024-01908-7)

[Rheological Properties of Small-Molecular Liquids at High Shear Strain Rates](https://www.mdpi.com/2073-4360/15/9/2166)


![Squalane viscosity and shear stress under various shear rates](/assets/viscosity_stress.png)
![Squalane's atom pairs orientation under different pressures by PCA dimension reduction](/assets/dist_backbone.png)

<!--
## MathJax

You can enable MathJax by setting `mathjax: true` on a page or globally in the `_config.yml`. Some examples:

[Euler's formula](https://en.wikipedia.org/wiki/Euler%27s_formula) relates the  complex exponential function to the trigonometric functions.

$$ e^{i\theta}=\cos(\theta)+i\sin(\theta) $$

The [Euler-Lagrange](https://en.wikipedia.org/wiki/Lagrangian_mechanics) differential equation is the fundamental equation of calculus of variations.

$$ \frac{\mathrm{d}}{\mathrm{d}t} \left ( \frac{\partial L}{\partial \dot{q}} \right ) = \frac{\partial L}{\partial q} $$

The [Schrödinger equation](https://en.wikipedia.org/wiki/Schr%C3%B6dinger_equation) describes how the quantum state of a quantum system changes with time.

$$ i\hbar\frac{\partial}{\partial t} \Psi(\mathbf{r},t) = \left [ \frac{-\hbar^2}{2\mu}\nabla^2 + V(\mathbf{r},t)\right ] \Psi(\mathbf{r},t) $$

## Code

Embed code by putting `{{ "{% highlight language " }}%}` `{{ "{% endhighlight " }}%}` blocks around it. Adding the parameter `linenos` will show source lines besides the code.

{% highlight c %}

static void asyncEnabled(Dict* args, void* vAdmin, String* txid, struct Allocator* requestAlloc)
{
    struct Admin* admin = Identity_check((struct Admin*) vAdmin);
    int64_t enabled = admin->asyncEnabled;
    Dict d = Dict_CONST(String_CONST("asyncEnabled"), Int_OBJ(enabled), NULL);
    Admin_sendMessage(&d, txid, admin);
}

{% endhighlight %}

## Gists

With the `jekyll-gist` plugin, which is preinstalled on Github Pages, you can embed gists simply by using the `gist` command:

{% gist 5555251 %}

## Images

Upload an image to the *assets* folder and embed it with `![title](/assets/name.jpg))`. Keep in mind that the path needs to be adjusted if Jekyll is run inside a subfolder.

A wrapper `div` with the class `large` can be used to increase the width of an image or iframe.

![Flower](https://user-images.githubusercontent.com/4943215/55412447-bcdb6c80-5567-11e9-8d12-b1e35fd5e50c.jpg)

[Flower](https://unsplash.com/photos/iGrsa9rL11o) by Tj Holowaychuk

## Embedded content

You can also embed a lot of stuff, for example from YouTube, using the `embed.html` include.

{% include embed.html url="https://www.youtube.com/embed/_C0A5zX-iqM" %}
-->
