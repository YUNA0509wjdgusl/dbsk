<head>
    <title>WEB1 - HTML</title>
    <meta charset="UTF-8">
    <style>
    body{
      margin:0;
    }
    a {
      color:black;
      text-decoration: none;
    }
    h1 {
      font-size:45px;
      text-align: center;
      border-bottom:1px solid gray;
      margin:0;
      padding:20px;
    }
    ol{
      border-right:1px solid gray;
      width:100px;
      margin:0;
      padding:20px;
    }
    #grid{
      display: grid;
      grid-template-columns: 150px 1fr;
    }
    #grid ol{
      padding-left:33px;
    }
    #grid #article{
      padding-left:25px;
    }
    @media(max-width:800px) {
        #grid{
      display: block;
        }
      #grid ol{
        border-right: none;
      }
      h1{
        border-bottom:none;
      }
    }
        a{
            color:black;
            text-decoration: none;
        }
    .saw{
        color: gray;
    }
    #active{
        color:red;
    }
        h1{
            font-size: 45px;
            text-align: center;
        }
    </style>
    </head>
    <body>
        <h1><a href="index.html">WEB</a></h1>
        <div id="gird">
    <ol>
        <li><a href="1.html" class="saw">HTML</a></li>
        <li><a href="2.html" class="saw" id="active">CSS</a></li>
        <li><a href="3.html">JAVACRIPT</a></li>
        </ol></div>
        <div id="abc"><h2>HTML</h2>
        <p><a href="https://www.w3.org/TR/2011/WD-html5-20110405/text-level-semantics.html#the-a-element" target="_blank" title="HTML5 specification">hypertext Markup Language (HTML)</a> is the standard markup Language for <strong>creating <u>web</u> pages</strong> and web applications. 
        web browsers erceive Html documents from a web server or from local storang and render them inti miltimesdia web pages. 
        HTML describes the structure of a web pagr semantically and originally included cues for the appearance of the document.
        <img src="coding.jpg" width="100%"></p>
        <p style="margin-top: 40px;">HTML elements are the building blocks of HTMLpages. With HTML constructs, images and other object, such asinteractive forms, 
        may be embedded into the rendered page. It provides a means to create structures documents by denotting structural semantics for 
        text such asheading, paragraphs, lists, links, quotes and items. HTML elements are delineated by tags, weitten using angle brackents.</p>
    </div>
    </body>
