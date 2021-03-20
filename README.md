### Darkula theme from Pycharm added ([Source](https://github.com/dunovank/jupyter-themes)).

```bash
jt -t darcula  -fs 12 -tfs 12 -nfs 12 -ofs 11 -dfs 11 -cellw 75% -cursc w -T |
jt -t onedork  -fs 12 -tfs 12 -nfs 12 -ofs 11 -dfs 11 -cellw 75% -T
```

##### In ~/.ipython/profile_defaut/startup/***.py : 

```python
from jupyterthemes import jtplot
jtplot.style(theme='darcula', context='notebook', ticks=True, grid=False) | 
jtplot.style(theme='onedork', context='notebook', ticks=True, grid=False)

# theme = (paper, notebook, talk, poster)
# figsize=(6, 4.5)
# fscale=1.4
# spines=False
# gridlines='--'
```
