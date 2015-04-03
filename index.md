---
layout: default
title: Home
---

# LSU Beamer Theme

Beamer Theme that I created for presentations using the color schemes of Louisiana State University.

## Usage
You can use either the LSU or Baton Rouge theme below. See the example PDF file for appearance.
 You will need use the color style file for both the themes. The LSU theme also requires 
the outer theme below as well as four logs for each of the four corners.  
If you do not use all four logos, how it might affect the contents in the header or footer. 
You can modify the outer theme if this causes a problem.

To use the theme, add the theme as you would any other Beamer theme

```LaTeX
\usetheme{LSU}

```
OR
```TeX
\usetheme{BatonRouge}
```


### Download Beamer Themes

 * [Color Scheme](color/beamercolorthemetigers.sty)
 * [Outer Theme](outer/beamerouterthemetigers.sty)
 * [Baton Rouge Theme](theme/beamerthemeBatonRouge.sty)
 * [LSU Theme](theme/beamerthemeLSU.sty)

### Download Examples

 * [Baton Rouge PDF](example/beamerthemeBatonRouge.pdf)
 * [Baton Rouge TeX](example/beamerthemeBatonRouge.tex)
 * [LSU TeX](example/beamerthemeLSU.tex) 
 * [LSU PDF](example/beamerthemeLSU.pdf)

## Changelog

 * v1.0: Initial version defines a color scheme using LSU's purple and gold colors for any beamer theme
 * v1.1: Created two themes that use the color scheme from v1.0
 * v1.2: Modify outer theme due to change in icon sizes

# LSU Powerdot
Powerdot Theme using LSU colors created for the LaTeX presentation. (Why? because I had some time to 
evaluate powerdot)

## Usage


 
 * [Download](powerdot-lsuloni.sty)

## Disclaimer

The following style files were created for personal use and are not endorsed by Louisiana State University, 
High Performance Computing at LSU or Center for Computation & Technology. Feel free to use or modify them for 
personal use.  
Moving these files to github now that I am no longer at LSU and I don't know how long my CCT website will 
be available. 

Good Luck and Go Gators!

## Author

Alex Pacheco  
Manager, Research Computing, Lehigh University  
Formerly: HPC User Services Consultant, Louisiana State University  


<!--
<div class="posts">
  {% for post in paginator.posts %}
  <article class="post">
    <h1 class="post-title">
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
    </h1>

    <time datetime="{{ post.date | date_to_xmlschema }}" class="post-date">{{ post.date | date_to_string }}</time>

    {{ post.content }}
  </article>
  {% endfor %}
</div>

<div class="pagination">
  {% if paginator.next_page %}
    <a class="pagination-item older" href="{{ site.baseurl }}page{{paginator.next_page}}">Older</a>
  {% else %}
    <span class="pagination-item older">Older</span>
  {% endif %}
  {% if paginator.previous_page %}
    {% if paginator.page == 2 %}
      <a class="pagination-item newer" href="{{ site.baseurl }}">Newer</a>
    {% else %}
      <a class="pagination-item newer" href="{{ site.baseurl }}page{{paginator.previous_page}}">Newer</a>
    {% endif %}
  {% else %}
    <span class="pagination-item newer">Newer</span>
  {% endif %}
</div>
-->
