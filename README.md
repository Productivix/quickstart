# quickstart
site de test Hugo multilingue

On Dec 01 2023 , the problem is that the 404 page is not generated : 
ex : http://localhost:1313/fr/any gives "Page Not Found"
and 
http://localhost:1313/404.html gives  :"404 page not found"

if you change :
defaultContentLanguageInSubdir = true  to false
you do not have this issue
