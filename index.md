<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script> <script type="text/x-mathjax-config"> MathJax.Hub.Config({ tex2jax: { skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'], inlineMath: [['$','$']] } }); </script>

## Assignment 1

```markdown
Syntax highlighted code block

# Question 1
## (a)

\begin{proof}
Given that the transform of $Z_{m \times n}$ such that $\widehat{Z}_{m \times n} = A_m Z A^\top_n$ where $\{A_n\}$ satisfies $A^\top_n A_n = D_n$ such that $D_n$ is diagonal. Want to show $Z = D^{-1}_m A^\top_m \widehat{Z} A_n D^{-1}_n$. 
Consider that
\begin{equation*}
\begin{split}
    D^{-1}_m A^\top_m \widehat{Z} A_n D^{-1}_n & = D^{-1}_m A^\top_m A_m Z A^\top_n A_n D^{-1}_n\\
    & = A_m A^\top_m A^\top_m A_m Z A^\top_n A_n A_n A^\top_n\\
    & = D^{-1}_m D_m Z A^\top_n A_n A_n A^\top_n\\
    & = I^{-1}Z D_n D^{-1}_n\\
    & = Z D_n D^{-1}_n\\
    & = ZI\\
    & = Z
\end{split}
\end{equation*}
Hence the original image can be constructed by $Z = D^{-1}_m A^\top_m \widehat{Z} A_n D^{-1}_n$.
\end{proof}

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/hdu214/STA410/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
