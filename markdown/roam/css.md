- mono themeset
    - [Dark Age Dracula](https://github.com/abhayprasanna/abhayprasanna.github.io)
        - ```css
@import url('https://abhayprasanna.github.io/dark-age-dracula.css');```
    - ```css
@import url('https://abhayprasanna.github.io/better-dark-age.css');

@import url('https://fonts.googleapis.com/css?family=Commissioner|Crimson+Text|Fira+Code|Bitter|Work+Sans');

@media (prefers-color-scheme: light) {
  :root {
    /* FONTS */
    --global-font             : "Iowan Old Style", serif, "PingFang SC", -apple-system, "SF UI Text", "Lucida Grande", STheiti, "Microsoft YaHei", sans-serif;
    --secondary-font          : 'Fira Code', monospace;
    --header-font             : 'Crimson Text', serif;
    /* WIDTH FIXES - default 568px,1032px - increase to increase WIDTH */
    --reduce-padding-right    : 3400px;
    --reduce-padding-left     : 3400px;
    /* COLORS - One light*/
    --page-links              : #585DCF;
    --attributes-color        : #986801;
    --external-links          : #50A14E;
    --links-hover             : #E4564A;
    --hashtags                : #A626A4;
    --body-text               : #292D31;
    --italics-color           : #E4564A;
    --bold-color              : #0184BC;
    --highlight-text-color    : #292D31;
    --highlighter             : #FFFF80;
    --background              : #FFFFFF;
    --sidebar-background      : #EAEAEB;
    --sidebar-text            : #292D31;
    --page-heading            : #2979ff;
    --daily-heading           : #2979ff;
    --headings                : #292D31;
    --bullets                 : #4078F2;
    --closed-bullets          : #4078F277;
    --references              : #4078F2;
    --block-reference-text    : #0184BC;
    --namespaces              : #E4564A;
    --all-pages-mentions      : #0184BC;
    --cursor                  : #292D31;
    --icons                   : #4078F2;
    --icons-hover             : #E4564A;
    --filter-icon             : #50A14E;
    /* FONT SIZES */
    --main-font-size          : 1.2em;
    --page-head-font-size     : 2.2em;
    --h1-font-size            : 2em;
    --h2-font-size            : 1.6em;
    --h3-font-size            : 1.2em;
    --sidebar-h1-size         : 2.2em;
    /* DROPDOWN MENU */
    --dropdown-menu-background: #EAEAEB;
    --dropdown-menu-highlight : #FAFAFA;
    --dropdown-menu-text      : #292D31;
    --dropdown-newpage        : #2979ff;
    /* SEARCH BAR */
    --search-bar-background   : #F7F8FA;
    --search-bar-text         : #292D31;
    /* KANBAN CARD COLORS */
    --kanban-main-background  : #FAFAFA;
    --kanban-column-background: #EAEAEB;
    --kanban-card-background  : #FAFAFA;
    --kanban-text-hover       : #E4564A;
  }
}
@media (prefers-color-scheme: light) {
  :root {
    /* FONTS */
    --global-font             : "Iowan Old Style", serif, "PingFang SC", -apple-system, "SF UI Text", "Lucida Grande", STheiti, "Microsoft YaHei", sans-serif;
    --secondary-font          : 'Fira Code', monospace;
    --header-font             : 'Bitter', serif;
    /* WIDTH FIXES - default 568px,1032px - increase to increase WIDTH */
    --reduce-padding-right    : 3400px;
    --reduce-padding-left     : 3400px;
    /* COLORS (HT: Jack Laing for [[Dracula Pro]] color theme) */
    --page-links              : #9580FF;
    --attributes-color        : #FFFF80;
    --external-links          : #8AFF80;
    --links-hover             : #92FFFF;
    --hashtags                : #FE7FBF;
    --body-text               : #F2F2F2;
    --italics-color           : #92FFFF;
    --bold-color              : #FF9580;
    --highlight-text-color    : #1B1A23;
    --highlighter             : #FFFF80;
    --background              : #1B1A23;
    --sidebar-background      : #2B2640;
    --sidebar-text            : #F2F2F2;
    --page-heading            : #9580FF;
    --daily-heading           : #9580FF;
    --headings                : #F2F2F2;
    --bullets                 : #7C6EAD;
    --closed-bullets          : #313340;
    --references              : #7C6EAD;
    --block-reference-text    : #FF9580;
    --namespaces              : #92FFFF;
    --all-pages-mentions      : #FF9580;
    --cursor                  : #F2F2F2;
    --icons                   : #7C6EAD;
    --icons-hover             : #92FFFF;
    --filter-icon             : #8AFF80;
    /* FONT SIZES */
    --main-font-size          : 1.2em;
    --page-head-font-size     : 2.2em;
    --h1-font-size            : 2em;
    --h2-font-size            : 1.6em;
    --h3-font-size            : 1.2em;
    --sidebar-h1-size         : 2.2em;
    /* DROPDOWN MENU */
    --dropdown-menu-background: #2B2640;
    --dropdown-menu-highlight : #1B1A23;
    --dropdown-menu-text      : #F2F2F2;
    --dropdown-newpage        : #9580FF;
    /* SEARCH BAR */
    --search-bar-background   : #1B1A23;
    --search-bar-text         : #F2F2F2;
    /* KANBAN CARD COLORS */
    --kanban-main-background  : #1B1A23;
    --kanban-column-background: #2A2C37;
    --kanban-card-background  : #1B1A23;
    --kanban-text-hover       : #81FFEA;
  }
}

span.rm-block-ref {
  border-bottom: 0.5px solid #D8E1E8;
}

[data-link-title^='🍚 今天'] {
  padding: 8px;
  color: gray !important;
  background: #C6D1D7;
}

[data-link-title^='🍚 今天']:before {
  content: '🌞 '
}
[data-link-title^='🍚 今天']:after {
  content: ' 🌑'
}```
- [[SmartBlocks]] 插件样式
    - ```css
.rm-bq {
    background-color: #F5F8FA !important;
    border-left: 5px solid #2196f3 !important;
  	color: black !important;
  	border-top-right-radius: 20px;
  	border-bottom-right-radius: 20px;
}```
- #good
- 
- 
- mermaid
    ```javascript
.rm-mermaid{
  background: transparent !important;
  min-width: 0px !important;
}

.rm-mermaid .node rect{
  stroke: #2A496F !important;
}

.rm-mermaid div
{
  color: #448889 !important;
  margin-right: 15px;
}

.rm-mermaid text
{
  fill: #34A5A5 !important;
  font-size: 25px !important;
}

.rm-mermaid rect{
  fill: transparent !important;
  stroke-width: 0px !important;
}

.rm-mermaid tspan{
  fill: #438BE0 !important;
  font-size: 20px !important;
}```
