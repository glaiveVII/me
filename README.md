# ME 

# theme : https://github.com/victoriadrake/hugo-theme-sam

# idea of cool website 
- https://www.di.ens.fr/~lelarge/
- https://www.joshpetty.io/

# launch local server
```
hugo server
```
Debug your site on http://localhost:1313. Any file changed will lead to website live update.

# test to build website in local
```
hugo
```
Your site files located on public folder.

# cleaning submodules if issues on the way you have imported them :
```
rm -rf themes
git submodule add https://github.com/xxx/gohugo-theme-xxx.git themes/xxx;\
# Edit your config.toml configuration file
# and add the xxx theme.
echo 'theme = "xxx"' >> config.toml
```
don’t forget to init and update the sub-module in git. 
You will then see the files locally and can tinker with them.
```
git submodule init
git submodule update --remote
```

# really well made cheat sheet to anticipate fix basic config errors :
https://dc-coder.com/post/hugo-cheat-sheet/
