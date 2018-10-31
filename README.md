# Full-Height-Grid-Layout
Simple CSS Grid template for a full screen layout that scales to any screen size. Utilizes 100% height and width, designed for webpages or applications that requires no scrolling.

## Info &amp; Notes
- Grid container is set to 100% height and width to body; Its configured with 10x10 rows and colunns with auto width and height.
- Grid template includes header, main body and footer section. 
- To get rid of the browser's default margin and padding:
```
body {
  margin: 0;
  width: 0;
}
```  
- Template can be easily modified with the predefined Sass variables.  


## Sass / scss
- Both grid.scss and grid.css files are included. 
- Using sass/scss is optional.
- Sass needs to be installed on your machine to use. [See sass-lang.com/install](https://sass-lang.com/install)
- Any code written or modified to grid.scss needs to be compiled to grid.css. To compile, go to project directory and: 
```
sass grid.scss grid.css
```
