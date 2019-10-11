<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script> <script type="text/x-mathjax-config"> MathJax.Hub.Config({ tex2jax: { skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'], inlineMath: [['$','$']] } }); </script>

## Assignment 1

# Question 1
## (a)
$Proof: $
Given that the transform of $Z_{m \times n}$ such that $\widehat{Z}_{m \times n} = A_m Z A^\top_n$ where $\{A_n\}$ satisfies $A^\top_n A_n = D_n$ such that $D_n$ is diagonal. Want to show $Z = D^{-1}_m A^\top_m \widehat{Z} A_n D^{-1}_n$. 
Consider that
    $$D^{-1}_m A^\top_m \widehat{Z} A_n D^{-1}_n & = D^{-1}_m A^\top_m A_m Z A^\top_n A_n D^{-1}_n$$
    $$& = A_m A^\top_m A^\top_m A_m Z A^\top_n A_n A_n A^\top_n$$
    $$& = D^{-1}_m D_m Z A^\top_n A_n A_n A^\top_n$$
    $$& = I^{-1}Z D_n D^{-1}_n$$
    $$& = Z D_n D^{-1}_n$$
    $$& = ZI$$
    $$& = Z$$
Hence the original image can be constructed by $Z = D^{-1}_m A^\top_m \widehat{Z} A_n D^{-1}_n$.

