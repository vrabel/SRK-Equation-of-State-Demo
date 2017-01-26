<style TYPE="text/css">
code.has-jax {font: inherit; font-size: 100%; background: inherit; border: inherit;}
</style>
<script type="text/x-mathjax-config">
MathJax.Hub.Config({
    tex2jax: {
        inlineMath: [['$','$'], ['\\(','\\)']],
        skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'] // removed 'code' entry
    }
});
MathJax.Hub.Queue(function() {
    var all = MathJax.Hub.getAllJax(), i;
    for(i = 0; i < all.length; i += 1) {
        all[i].SourceElement().parentNode.className += ' has-jax';
    }
});
<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>

# SRK Equation of State Demo
This project is the first in series of exercises as part of the course **Programming for Chemical Engineering Applications** taught at the
University of Notre Dame by [Jeffery Kantor](https://github.com/jckantor).

The goal of this project is to demonstrate the **Soave-Redlich-Kwong equation** of state with a small, nonpolar molecule at a set pressure and temperature, solving for the molar volume. The intended audience is first or second year engineers who want to see how changing the appropriate parameters affects the P-T or P-V plots.

$$P = $$
