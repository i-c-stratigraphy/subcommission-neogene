# Neogene Subcommission Website
The small website for the Neogene subcommission of the International Commission on Stratigraphy, online at <http://neogene.stratigraphy.org>.


## Content
Content for this website is managed by the [Neogene subcommission of the ICS](https://stratigraphy.org/subcommissions#neogene).

See Contacts below.


## Technical website operations
This is a [Jekyll](https://jekyllrb.com/) *static site generator* website which means the source files are pretty much simplified HTML pages - [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)-formatted text files - which you can see stored in the [pages/](pages/) folder. These are combined with a very simple template to add headers & footers to all pages and produce the final HTML web pages which are then delivered online with a web server. We are using the built in [GitHub Pages](https://pages.github.com/).

This subcommission's website is hosted within the ICS's set of code repositories, see <https://github.com/i-c-stratigraphy/subcommission-neogene>.

Setup:

`bundle install`  
`bundle exec jekyll new --force --skip-bundle .`  
`bundle install`  
`bundle update`  
`bundle add webrick`  
`bundle exec jekyll new --force --skip-bundle .`  
`bundle add webrick`  

Running the site locally:

`bundle exec jekyll serve`


## License & Rights
The content of this repository is licensed using the Creative Commons Attribution 4.0 license:

* <https://creativecommons.org/licenses/by/4.0/>

See the [local copy of the license deed](LICENSE) for details.

&copy; International Commission on Stratigraphy 2020, all rights reserved


## Support and contacts
*For website content:*  
**Prof. Elena Turco**  
Neogene Subcommission Vice-Chair  
Università degli Studi di Parma  
<elena.turco@unipr.it>  


*For website technical matters:*  
**Dr Nicholas Car**  
ICS Webmaster  
<nicholas.car@surroundaustralia.com>  
