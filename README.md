# SWPU Thesis LaTex Macro Package

用于学位论文模板的宏包。

## 使用方法

确保安装了最新版本的`TexLive`以及本宏包依赖的字体库。

使用 `xelatex`编译`swputhesis.ins`
生成`swputhesis.cls`。

```bash
xelatex swputhesis.ins
```

使用`Latexmk`编译`swputhesis.dtx`生成本用户手册`swputhesis.pdf`。

```bash
latexmk -xelatex swputhesis.dtx
```

## Refs

* [How to Package Your LaTeX Package](https://mirrors.sjtug.sjtu.edu.cn/ctan/info/dtxtut/dtxtut.pdf)
