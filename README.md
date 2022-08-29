# HTML-Notes
<!DOCTYPE html>
<html>
        <head>
        <title>Page 1 HTML</title>
        </head>
        <body>
        <pre>
               <h1>Heading tag which leads H1 to H6 which define the size of headings</h1>
               <hr><!--horizontal rule-->
               <p>Paragraph</p> 
               <p width="100px">paragraph with attribute</p>
               <br><!--break the paragraph-->
               <pre>Used for display the content on website as it is written code</pre>
               <b>Bold</b>
               <strong>like a "BOLD" tag but the particular content DOMOINATE into the paragraph which is good for "SEO" and Screen Reading</strong>
               <i>italic</i>
               <em>like a "ITALIC" tag but the particular content DOMOINATE into the paragraph which is good for "SEO" and Screen Reading</em>
               <small>smaller then regular font</small>
               <mark>Highlight the content</mark>
               <del>deleted content</del>
               <ins>inserted content</ins>
               x<sub>2</sub> <!--base creation-->
               x<sup>2</sup> <!--power creation-->
               <q>quotation tag display with double quote on web page</q>
               <blockquote>when we use quotation of other person it display on web page with margin without source</blockquote>
               <blockquote cite="https://www.google.com">when we use quotation of other person it display on web page with margin with source</blockquote>
               <abbr title="world health organization">WHO</abbr>  <!--use for demonstrate any word or full form-->
               <address>174 , Indarpuri , Bhopal</address>
               <cite>the lost kid </cite>is written by ______   <!--behave like a title-->
               <a href="https://www.google.com">Read more</a> <!--use for create a link in same tab without title-->
               <a href="https://www.google.com" target="_blank">Read more</a> <!--use for create a link in new tab -->
               <a href="https://www.google.com" target="_blank" title="Go to google.com">Read more</a> <!--use for create a link in new tab with title -->
               <a href="#local">read more </a><!--clicking on read more button we reach on the content of local link-->
               <p>Lorem ipsum dolor sit, amet  </p>
               <p id="local">this content is part of local link name as 'local'</p><!--for local link firstly have to make a id after that put the id name insted of link with # sign-->
               <p><!--creating a email link without subject-->
               contact us on <a href="mailto:princerajnri@gmail.com"> princerajnri@gmail.com</a>
               </p>
               <p><!--creating a email link with subject-->
               contact us on <a href="mailto:princerajnri@gmail.com?subject=hello I am Prince Kumar"> princerajnri@gmail.com</a>
               </p>
               <img src="C:\Users\princ\OneDrive\Desktop\py1.jpeg"> <!--use for inserting image without description-->
               <img src="C:\Users\princ\OneDrive\Desktop\py1.jpeg" alt="logo" width="100" height="100"> <!--use for inserting image with description-->
               <marquee direction="right">this is a moving test</marquee><!--right now this tag is not availeble for html directio=up,down,right,left-->
<!----------ordered list this by default in the form of integer but we can cahnge in various form -->
               <ol>
                       <li>cofee</li>
                       <li>milk</li><!--default ordered list-->
                       <li>tea</li>
               </ol>
               <ol type="I">
               <li>cofee</li>
               <li>milk</li><!--type of ordered list "i for roman" "a for alphabatical order" -->
               <li>tea</li>
               </ol>
               <ol>
                <li>cofee
                        <ol>
                                <li>black cofee</li>
                                <li>cold cofee</li>   <!--list inside the list-->
                        </ol>
                </li>
                <li>milk</li>
                <li>tea</li>
               </ol>

        
<!--------------unordered list------------------------>
               <ul style="list-style-type:circle;">
                       <li>coffee
                               <ul>
                                       <li>black</li>
                                       <li>cold</li>
                               </ul>
                       </li>
                       <li>tea</li>
                       <li>milk</li>
               </ul>
               <!--description list = list of content with description -->
               <dl>
                       <dt style="color:blue"><b>coffee</b></dt>
                       <dd>-black hot drink</dd>
                       <dt>milk</dt>
                       <dd>-white in colour</dd>
                       <dt>tea</dt>
                       <dd>-black tea without sugar</dd>
               </dl>
<!-----------HTML Table------------------------------>
               <table border="1"> <!--attribute border-->
               <thead style="color:red;">
                       <tr><!--introducing column-->
                               <th>row1</th>
                               <th>column1</th> 
                               <th>column2</th>
                               <th>column3</th>
                       </tr>
                </thead>
                <caption>table example</caption> <!--table name -->
                <tbody style="color:rgb(45, 9, 248);">       
                        <tr>
                                <th>row2</th>
                                <td>
                                        <table border="1">
                                                <tr>
                                                        <td>col1</td>
                                                        <td>col2</td>
                                                </tr>
                                                <tr>
                                                        <td>col3</td>
                                                        <td>col4</td>
                                                </tr>
                                        </table>
                                </td>
                                <td>data2</td>
                                <td>data3</td>
                       </tr>
                       <tr>
                                <th>row3</th>
                                <td><img src="C:\Users\princ\OneDrive\Desktop\py1.jpeg" alt=""></td>   <!--we can put image and link as well in row or column-->
                                <td colspan="2">
                                        <a href="www.google.com">google</a> <!--colspan is used for combine the column and row span is used for combine the row-->
                                </td>
                                <td>data3</td>
                       </tr>
                       <tr>
                                <th>row4</th>
                                <td rowspan="2">data1</td>
                                <td>data2</td>
                                <td>data3</td>
                       </tr>
                </tbody>       

               </table>
               


        </pre>
<!---------------  DIV( block element ) AND SPAN ( inline element )------------>
<!---->
                <div style="border:1px solid red;">random text</div>   <!--start with new line but not in case of span and the border will take whole width in div, In span it will take only text width -->
                <span style="border:1px solid red;">random text</span>
<!--------- iframe tag ---------->
                <iframe src="link" height="500" width="500"></iframe> 
        <!--use for inserting a website on webpage-->
                <audio controls>
                        <source src="C:\Users\princ\Downloads\y2meta.com - Rangi Saari _ Kanishk Seth & Kavita Seth _ Official Music Video (128 kbps).mp3" type="audio/mpeg"> <!--insering audio file-->
                        <iframe width="560" height="315" src="https://www.youtube.com/embed/-c1MigLf3Ug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </body>
</html>

<!---Element- anything which is written in html 
Attribute - additional info about the element 
<tag_name>content</tag_name>
<tag_name attribute_1="value" attribute_2="value">content</tag_name> --->



<!-- iserting the video on web page -->
<!DOCTYPE html>
<html>
    <head>page 2</head>
        <title>PAGE 2 HTML</title>
        <body>
            <video controls>
                <source src="C:\Users\princ\OneDrive\Desktop\video.mp4" type="video/mp4">
            </video>
            <video controls>
                <source src="C:\Users\princ\OneDrive\Desktop\video.mp4" type="video/mp4">
            </video>
            <video autoplay>
                <source src="C:\Users\princ\OneDrive\Desktop\video.mp4" type="video/mp4">
            </video>
            <video width="1000" height="500" controls>
                <source src="C:\Users\princ\OneDrive\Desktop\video.mp4" type="video/mp4">
            </video>
<!-------embed pdf (embed , iframe, object)---------->
            <embed src="C:\Users\princ\OneDrive\Desktop\exam fee sourabh.pdf" type="application/pdf" width="1000" height="500">
            <iframe src="C:\Users\princ\OneDrive\Desktop\exam fee sourabh.pdf" type="application/pdf">
            <object data="C:\Users\princ\OneDrive\Desktop\exam fee sourabh.pdf" type="application/pdf">
<!--    inserting youtube link     -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-c1MigLf3Ug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<!----------HTML entities -----serch on google for further information----->
            <!--name -->
            &lt;div&gt;
            <!--number -->
            &#60;div&#62;
            <!-- HTML Symbols-->
            &copy;    <!--copyright-->
            &#8508;   <!--mathematical symbols , search on google for symbol codes-->
            <!--emoji in HTML-->
            &#128516; <!--search on google for emoji codes -->
        </body>
        <body>
            <!--HTML image map(putting link on images)-->
            <a href="https://www.amazon.com" target="_blank">
            <img src="hcl-technologies--600.png" alt="">
            </a>
            <img src="hcl-technologies--600.png" alt="" usemap="#hcl">
            <map name="hcl">
                <area shape="rect" coords="34,44,250,350" href="https://www.amazon.com/s?k=laptop&crid=1KNXCL64J93PP&sprefix=lapto%2Caps%2C588&ref=nb_sb_noss_2" target="_blank">
                <area shape="rect" coords="290,172,333,250" href="https://www.amazon.com/s?k=mobile&crid=24X35F3N8YV0K&sprefix=mobi%2Caps%2C721&ref=nb_sb_noss" target="_blank">
                
            </map>
            <!-- FORM -->
            <form>
                <div>
                    name:
                    <input type="text">
                    <div>
                        <br>
                        <input type="submit" value="submit form">
                    </div>
                </div>
            </form>
            <form>
                <div>
                    text:
                    <input type="text">
                </div>
                <div>
                    submit button:
                    <input type="submit"><br>
                </div>
                <div>
                    colour:
                    <input type="color"><br>
                </div>
                <div>
                    date:
                    <input type="date"><br>
                    <div>
                        email:
                        <input type="email"><br>
                    </div>
                    <div>
                        hidden:
                        <input type="hidden" value="delhi"><br>
                    </div>
                    <div>
                        number:
                        <input type="number"><br>
                    </div>
                    <div>
                        password:
                        <input type="password"><br>
                    </div>
                    <div>
                        reset:
                        <input type="reset"><br>
                    </div>
                    <div>
                        time:
                        <input type="time"><br>
                    </div>
                    <div>
                        URL:
                        <input type="url"><br>
                    </div>
                    <div>
                        range:
                        <input type="range" min="1000" max="5000"><br>
                    </div>
                </div>
            </form>
            <form enctype="multipart/form-data">
                <input type="file" multiple>
            </form>
            <form>
                <input type="text" value="prince" readonly>
                <input type-="submit" value="Go">
            </form>
        </body>
</html>
