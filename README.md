~/.local/share/jupyter/lab/themes/@jupyterlab/theme-dark-extension$


these values are just examples at this point, the values would have changed.
Putting these here to point out the locations of some of the "main" css variables

```
  /* Layout
   *
   * The following are the main layout colors use in JupyterLab. In a light
   * theme these would go from light to dark.
   */
  /* my custom color */
  /* background color */
  --jp-layout-color0: hsl(32, 6%, 12%);
  /* sidebar and menu bar color */
  --jp-layout-color1:  hsl(32, 6%, 12%);
```

```

  /* Brand/accent */
  /* my custom color */
  /* purple */
  /* --my-brand-color:hsl(270, 100%, 80%);  */
  /* green */
  --my-brand-color:hsl(100, 50%, 70%);
  --jp-brand-color0: var(--my-brand-color);
  --jp-brand-color1: var(--my-brand-color);
  --jp-brand-color2: var(--my-brand-color);
  --jp-brand-color3: var(--my-brand-color);
  --jp-brand-color4: var(--my-brand-color);
```


```
/* Defaults use Material Design specification */
/* my custom colors */
/* --my-main-color:#D1B498; */
--my-main-color:#D6C8BC;
--jp-content-font-color0: var(--my-main-color);
--jp-content-font-color1: var(--my-main-color);
--jp-content-font-color2: var(--my-main-color);
--jp-content-font-color3: var(--my-main-color);
```

```
  /* Cell specific styles */
  /* my custom color */
  --jp-cell-editor-background: hsl(10, 8%, 10%);

```


```
  /* Code mirror specific styles */
  /* my custom colors */
  /* bright purple color hex #AA22FF */
  --jp-mirror-editor-keyword-color: #C37D3B;
  --jp-mirror-editor-atom-color: #E7A0E9 ;
  --jp-mirror-editor-number-color: #89FFDC;
  --jp-mirror-editor-def-color: #C37D3B;
  --jp-mirror-editor-variable-color:#51D4FF;
  --jp-mirror-editor-variable-2-color:#51D4FF;
  --jp-mirror-editor-variable-3-color: #51D4FF;
  --jp-mirror-editor-punctuation-color:  #51D4FF;
  --jp-mirror-editor-property-color:#EBA22C;
  --jp-mirror-editor-operator-color: #C0A57A;
  --jp-mirror-editor-comment-color: #584E4C;
  --jp-mirror-editor-string-color: #DCADF0;
  --jp-mirror-editor-string-2-color:#B656DF;
  --jp-mirror-editor-meta-color: #a2f;
  --jp-mirror-editor-qualifier-color: #AA22FF;
  --jp-mirror-editor-builtin-color: #83D0E9;
  --jp-mirror-editor-bracket-color: #997;
  --jp-mirror-editor-tag-color: var(--md-green-700, #388e3c);
  --jp-mirror-editor-attribute-color:#AA22FF;
  --jp-mirror-editor-header-color:#AA22FF;
  --jp-mirror-editor-quote-color: #AA22FF;
  --jp-mirror-editor-link-color:#AA22FF;
  --jp-mirror-editor-error-color:#AA22FF;
  --jp-mirror-editor-hr-color: #AA22FF;
```
