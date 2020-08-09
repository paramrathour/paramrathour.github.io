---
title: Quartic Roots
---
<script>
MathJax = {
tex: {inlineMath: [['$', '$'], ['\\(', '\\)']]}
};
</script>
<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
<p>
\begin{align}
    r_1&=-\frac{a}{4}
    -\frac{1}{2}\sqrt{\frac{a^2}{4}-\frac{2b}{3}+\frac{2^{\frac{1}{3}}\left(b^2-3ac+12d\right)}{3\left(2b^3-9abc+27c^2+27a^2d-72bd+\sqrt{-4\left(b^2-3ac+12d\right)^3+\left(2b^3-9abc+27c^2+27a^2d-72bd\right)^2}\right)^{\frac{1}{3}}}+\left(\frac{2b^3-9abc+27c^2+27a^2d-72bd+\sqrt{-4\left(b^2-3ac+12d\right)^3+\left(2b^3-9abc+27c^2+27a^2d-72bd\right)^2}}{54}\right)^{\frac{1}{3}}}
    -\frac{1}{2}\sqrt{\frac{a^2}{2}-\frac{4b}{3}+\frac{2^{\frac{1}{3}}\left(b^2-3ac+12d\right)}{3\left(2b^3-9abc+27c^2+27a^2d-72bd+\sqrt{-4\left(b^2-3ac+12d\right)^3+\left(2b^3-9abc+27c^2+27a^2d-72bd\right)^2}\right)^{\frac{1}{3}}}-\left(\frac{2b^3-9abc+27c^2+27a^2d-72bd+\sqrt{-4\left(b^2-3ac+12d\right)^3+\left(2b^3-9abc+27c^2+27a^2d-72bd\right)^2}}{54}\right)^{\frac{1}{3}}-\frac{-a^3+4ab-8c}{4\sqrt{\frac{a^2}{4}-\frac{2b}{3}+\frac{2^{\frac{1}{3}}\left(b^2-3ac+12d\right)}{3\left(2b^3-9abc+27c^2+27a^2d-72bd+\sqrt{-4\left(b^2-3ac+12d\right)^3+\left(2b^3-9abc+27c^2+27a^2d-72bd\right)^2}\right)^{\frac{1}{3}}}+\left(\frac{2b^3-9abc+27c^2+27a^2d-72bd+\sqrt{-4\left(b^2-3ac+12d\right)^3+\left(2b^3-9abc+27c^2+27a^2d-72bd\right)^2}}{54}\right)^{\frac{1}{3}}}}}\\
    r_2&=-\frac{a}{4}
    -\frac{1}{2}\sqrt{\frac{a^2}{4}-\frac{2b}{3}+\frac{2^{\frac{1}{3}}\left(b^2-3ac+12d\right)}{3\left(2b^3-9abc+27c^2+27a^2d-72bd+\sqrt{-4\left(b^2-3ac+12d\right)^3+\left(2b^3-9abc+27c^2+27a^2d-72bd\right)^2}\right)^{\frac{1}{3}}}+\left(\frac{2b^3-9abc+27c^2+27a^2d-72bd+\sqrt{-4\left(b^2-3ac+12d\right)^3+\left(2b^3-9abc+27c^2+27a^2d-72bd\right)^2}}{54}\right)^{\frac{1}{3}}}
    +\frac{1}{2}\sqrt{\frac{a^2}{2}-\frac{4b}{3}+\frac{2^{\frac{1}{3}}\left(b^2-3ac+12d\right)}{3\left(2b^3-9abc+27c^2+27a^2d-72bd+\sqrt{-4\left(b^2-3ac+12d\right)^3+\left(2b^3-9abc+27c^2+27a^2d-72bd\right)^2}\right)^{\frac{1}{3}}}-\left(\frac{2b^3-9abc+27c^2+27a^2d-72bd+\sqrt{-4\left(b^2-3ac+12d\right)^3+\left(2b^3-9abc+27c^2+27a^2d-72bd\right)^2}}{54}\right)^{\frac{1}{3}}-\frac{-a^3+4ab-8c}{4\sqrt{\frac{a^2}{4}-\frac{2b}{3}+\frac{2^{\frac{1}{3}}\left(b^2-3ac+12d\right)}{3\left(2b^3-9abc+27c^2+27a^2d-72bd+\sqrt{-4\left(b^2-3ac+12d\right)^3+\left(2b^3-9abc+27c^2+27a^2d-72bd\right)^2}\right)^{\frac{1}{3}}}+\left(\frac{2b^3-9abc+27c^2+27a^2d-72bd+\sqrt{-4\left(b^2-3ac+12d\right)^3+\left(2b^3-9abc+27c^2+27a^2d-72bd\right)^2}}{54}\right)^{\frac{1}{3}}}}}\\
    r_3&=-\frac{a}{4}
    -\frac{1}{2}\sqrt{\frac{a^2}{4}-\frac{2b}{3}+\frac{2^{\frac{1}{3}}\left(b^2-3ac+12d\right)}{3\left(2b^3-9abc+27c^2+27a^2d-72bd+\sqrt{-4\left(b^2-3ac+12d\right)^3+\left(2b^3-9abc+27c^2+27a^2d-72bd\right)^2}\right)^{\frac{1}{3}}}+\left(\frac{2b^3-9abc+27c^2+27a^2d-72bd+\sqrt{-4\left(b^2-3ac+12d\right)^3+\left(2b^3-9abc+27c^2+27a^2d-72bd\right)^2}}{54}\right)^{\frac{1}{3}}}
    -\frac{1}{2}\sqrt{\frac{a^2}{2}-\frac{4b}{3}+\frac{2^{\frac{1}{3}}\left(b^2-3ac+12d\right)}{3\left(2b^3-9abc+27c^2+27a^2d-72bd+\sqrt{-4\left(b^2-3ac+12d\right)^3+\left(2b^3-9abc+27c^2+27a^2d-72bd\right)^2}\right)^{\frac{1}{3}}}-\left(\frac{2b^3-9abc+27c^2+27a^2d-72bd+\sqrt{-4\left(b^2-3ac+12d\right)^3+\left(2b^3-9abc+27c^2+27a^2d-72bd\right)^2}}{54}\right)^{\frac{1}{3}}+\frac{-a^3+4ab-8c}{4\sqrt{\frac{a^2}{4}-\frac{2b}{3}+\frac{2^{\frac{1}{3}}\left(b^2-3ac+12d\right)}{3\left(2b^3-9abc+27c^2+27a^2d-72bd+\sqrt{-4\left(b^2-3ac+12d\right)^3+\left(2b^3-9abc+27c^2+27a^2d-72bd\right)^2}\right)^{\frac{1}{3}}}+\left(\frac{2b^3-9abc+27c^2+27a^2d-72bd+\sqrt{-4\left(b^2-3ac+12d\right)^3+\left(2b^3-9abc+27c^2+27a^2d-72bd\right)^2}}{54}\right)^{\frac{1}{3}}}}}\\
    r_4&=-\frac{a}{4}
    -\frac{1}{2}\sqrt{\frac{a^2}{4}-\frac{2b}{3}+\frac{2^{\frac{1}{3}}\left(b^2-3ac+12d\right)}{3\left(2b^3-9abc+27c^2+27a^2d-72bd+\sqrt{-4\left(b^2-3ac+12d\right)^3+\left(2b^3-9abc+27c^2+27a^2d-72bd\right)^2}\right)^{\frac{1}{3}}}+\left(\frac{2b^3-9abc+27c^2+27a^2d-72bd+\sqrt{-4\left(b^2-3ac+12d\right)^3+\left(2b^3-9abc+27c^2+27a^2d-72bd\right)^2}}{54}\right)^{\frac{1}{3}}}
    +\frac{1}{2}\sqrt{\frac{a^2}{2}-\frac{4b}{3}+\frac{2^{\frac{1}{3}}\left(b^2-3ac+12d\right)}{3\left(2b^3-9abc+27c^2+27a^2d-72bd+\sqrt{-4\left(b^2-3ac+12d\right)^3+\left(2b^3-9abc+27c^2+27a^2d-72bd\right)^2}\right)^{\frac{1}{3}}}-\left(\frac{2b^3-9abc+27c^2+27a^2d-72bd+\sqrt{-4\left(b^2-3ac+12d\right)^3+\left(2b^3-9abc+27c^2+27a^2d-72bd\right)^2}}{54}\right)^{\frac{1}{3}}+\frac{-a^3+4ab-8c}{4\sqrt{\frac{a^2}{4}-\frac{2b}{3}+\frac{2^{\frac{1}{3}}\left(b^2-3ac+12d\right)}{3\left(2b^3-9abc+27c^2+27a^2d-72bd+\sqrt{-4\left(b^2-3ac+12d\right)^3+\left(2b^3-9abc+27c^2+27a^2d-72bd\right)^2}\right)^{\frac{1}{3}}}+\left(\frac{2b^3-9abc+27c^2+27a^2d-72bd+\sqrt{-4\left(b^2-3ac+12d\right)^3+\left(2b^3-9abc+27c^2+27a^2d-72bd\right)^2}}{54}\right)^{\frac{1}{3}}}}}
\end{align}
</p>