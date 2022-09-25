# HTML Getting Started
 Learning basics

 Semantic Tags:
 <nav></nav>
 <header></header>
 <main></main>
 <footer></footer>
 <section>
  1. It is a semantic element as it clearly 
    describes its meaning to both, the browser 
    and the developer. 
 2. The content of a semantic element shares 
     a single theme.
 </section>
 <aside></aside>

 #Special Characters:

 <!-- &nbsp;

 &lt; &gt;

 he&apos;s -->

# ==>CSS Units:
      ###1)Absolute Unites: 
                        -cm
                        -inch
                        -px = 1/96 inch;

      ###2)Relative Units:
                        % : we can use "%" for percentage of parent unit.
                        50% means 50% of parent size;

      Viewport (vw, vh) : viewport means visible area of browser,
                          100vw,100vh means complete area of browser.
                          75vw,100vh means 75% of width 
                                        &  100% of height of browser.

      rem : It is relative to the font size of the root element i.e. root element .

            1rem = font size of root element. 

      em : It is relative to Parent.

# ==>CSS Add Border to an Elements:
      border-width = 10px;
      border-style = solid;
      border-color = blue;

    ->instead of writing all 3 parameters on seperate lines we can write it on single line;
      border = 10px solid blue;
      border-radius: 10px;


# ==>Text Styling Using CSS :
      color
      font-size
      fonr-weight: bold/bolder/normal  
                    font weight can be ranged from 100(thinnest)-900(thickest)

      text-align
      line-height: distance bw lines in px or rem;
      word-spacing:
      text-transform:uppercase/lowercase/Capitalize;
      text-decoration


# ==>Adding Background to an element:
      background-image: url()
      beackground-repeat: no-repeat;
      background-position:centre/top/left/right/top ;
      background-size: auto/cover/contain;
      background-attachment: scroll/fixed


# ==> Margins & Padding:
      Margin: It is nothing but space around that element i.e. outside;
              margin: 10px (all side)
              margin: 10px(top & bottom) 10px(left & right)
              margin: 10px(top) 20px(left&right) 30px(bottom)
              margin: 10px 20px 30px 40px;
              margin-top;
              margin-bottom;

              vertical margins gets colapsed not added. 
              horizontal margins gets add-up.
      
      Padding: It decides space within element;

# ==> Display:(inline, block, inline-block)
            we cannot set height & width of Inline elements;


# ==> Position Property:
      static: exact position
      relative: relative to its original position
      absolute: relative to its parent
      fixed: will have fixed position on viewport
      sticky: after certain threshhold behaves like fixed.
            
