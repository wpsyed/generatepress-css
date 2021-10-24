.entry-content p a, .entry-content li a, .entry-summary a, .nav-links a, .site-info a {
    border-bottom: 2px solid rgba(35, 117, 214, 0.4);
}
/* fix alignfull class too wide */
body {
overflow-x: hidden;
}
.separate-containers .inside-article {
    border-bottom: 1px solid rgba(0,0,0,.05);
}
.author-description {
    margin-bottom: 5px;
}
.author-box {
    padding: 3%;
    margin-top: 25px;
    display: flex;
    flex-wrap: wrap;
background-color: none;
    border: double 9x green;
    border-radius: 5px;
}
.author-box a {
}
.author-box .avatar {
    width: 55px;
    border-radius: 80%;
    margin-right: 10px;
}
h5.author-title {
    margin-bottom: 0.2em;
	  font-size: 25px;
	  font-weight: Bold
}
.sidebar .widget {
    padding: 15px;
    border:1px solid rgba(1,1,,.05);
    border-radius: 5px;
}
/*sticky widget*/
@media (min-width: 769px) {
 .site-content {
 display: flex;
 }
.inside-right-sidebar {
 height: 99%;
 }
.inside-right-sidebar aside:last-child {
 position: -webkit-sticky;
 position: sticky;
 top: 50px;
 }
 }
/*code blocks and snippets*/
 code {
     background: rgba(0,0,0,.05);
     padding: 2px;
}
.wp-block-preformatted code, .wp-block-code code {
     background: none !important;
}
 blockquote {
     font-size: 1em !important;
}
 .gb-highlight, .highlight, mark {
     background: #FAF3C4;
     padding: 4px;
}
.nav-links .page-numbers:not(.next):not(.prev) {
    display: none;
}
 .no-border a, .no-border a:visited {
     color: #4c5357 !important;
     border-bottom: none !important;
}
/*blog*/
 .read-more {
     margin-top: 5%;
     float: right;
}
.wp-show-posts a {
    font-size: 20px;
    line-height: 0.8em;
	}	
@media (max-width: 768px) {
	p {	
        font-size: 18px;
}
}
.related {
    font-weight: 600;
    box-shadow: 0 4px 15px rgba(0,0,0,.1);
    color: #16a085;
    padding: 15px;
    background-color: gre ;
    border-left: 5px solid #F26C4F;;
    font-size: 19px;
}
.sidebar .widget {
    padding: 15px;
    border:1px solid rgba(0,0,0,.05);
    border-radius: 4px;
    box-shadow: 0 0 27px 0 rgb(214 231 233 / 52%);
}
body {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
}
