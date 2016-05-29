## Latex Packages

*Note:* I use the `MiKTeX` distribution of latex on primarily windows machines. Whatever tools **you** use, you should know how/where to put the `.sty` files in order to use them for your templates. Below I explain how to get these files working for me.

### Using `MiKTeX` to set locations for style files.

#### Adding this repo to root.
1. `MiKTeX` always looks for files nested in folders of the following structure: `tex/latex/`.
2. As such, you need to add this repository to `MikTek`'s collection of `roots`.
3. Run `mo.exe`. This opens up `MiKTeK` options. 
4. Click on the roots tab. 
5. Click `Add...`.
6. Add this repository to the list. On my machine, path is `T:\GitProjects\Latex-Packages`.
7. Click `Apply`.

You will only ever have to do this once.
#### Adding packages.
If the folder of this repo is contained in the root list, any changes to **files** will automatically be taken care of.
However if **files** get added or deleted from this, you will need to force `MiKTeK` to refresh. To do this:

1. Run `mo.exe`. This opens up `MiKTeK` options. 
2. Go to the General tab.
3. Click Refresh FNDB.

*Note:* Don't put `.tex` files in directories on the root. I can't explain why but files won't compile unless they are outside these folders.
