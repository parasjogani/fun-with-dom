# Dom Manipulation Assignment

1. Webiste Name: [Dev To](https://dev.to/)

### Topics

    - Query Selctory, Inner HTML

### Sample Image

![Sample One](./Pic1.png)

### Tasks

        Target the Top description div and change the DEV Community to <Your_Name> and description to your passion

### Output

![Output](./Pic2.png)

### Code
```
document.querySelector(".side-bar .crayons-card .crayons-subtitle-2").innerHTML = "Paras Jogani"

document.querySelector(".side-bar .crayons-card .color-base-70").innerHTML = "I Write Code"
```
### Change OUTPUT

![Change Output](./change12.png)

2. Website Name: [Apple](https://support.apple.com/en-in)

### Task

![Store](./Picture_3.png)

### Fetch all the product name and store in an array

### Output

['iPhone', 'Mac', 'iPad', 'Watch', 'AirPods', 'Music', 'TV']

### Code
```
let arr = [];
document.querySelectorAll(".as-imagegrid-item").forEach((e) => {arr.push(e.innerText.replace("\nSupport", ""))})
console.log(arr)
```

### Change OUTPUT

![Change Output](./change3.png)


3. Webiste Name: [Youtube Support](https://support.google.com/youtube/)

### Topics

    - Get Element By Id, Create Element, Create Text Node, Append Child

### Sample Image

![Sample One](./Pic4.png)

### Tasks

     Add another FAQ 'My New FAQ' to the list

### Output

![Output](./Pic5.png)

### Code
```
const conid = document.getElementById("hcfe-content");

const path = document.querySelector(".primary-container .page-width-container .main-content .article .accordion-homepage");
const newsec = document.createElement("section");
newsec.className = "parent";
newsec.innerHTML = "<h3>My New FAQ</h3>";
path.append(newsec)

```

### Change OUTPUT

![Change Output](./change45.png)

4. Webiste Name: [OnePlus](https://www.oneplus.in/support)

### Topics

     Query Selector, InnerText

### Sample Image

![Sample One](./Pic6.png)

### Tasks

      Change the contact number

### Output

![Output](./Pic7.png)

### Code

```
document.querySelector(".customer-support .service-number").innerText = "+91 9887766554";

```

### Change OUTPUT

![Change Output](./change67.png)


5. Webiste Name: [Samsung](https://www.samsung.com/in/offer/online/samsung-fest/)

### Topics

       getElementById, createElement, InnerText, append, setAttribute

### Sample Image

![Sample One](./Pic8.png)

### Tasks

     Target the main div of card and change the Button text to Check out

### Output

![Output](./Pic9.png)

### Code

```
document.querySelector(".mytabs .diwali-deals-product-sale-pro .diwali-deals-product-sale-btn").innerText = "Check Out";
```

### Change OUTPUT

![Change Output](./change89.png)

6. Webiste Name: [Adidas](https://www.adidas.co.in/)

### Topics

    -   Query Selector, Event listeners, Changing Styles

### Sample Image

![Sample One](./Pic10.png)

### Tasks

     Target the search box and on hover change thebackground color to red.

### Output

![Output](./Pic11.png)

### Code

```
document.querySelector(".searchinput___19uW0").addEventListener("mouseover", function() {document.querySelector(".searchinput___19uW0").style.backgroundColor = "red"});
```

### Change OUTPUT

![Change Output](./change1011.png)

7. Webiste Name: [MDN Web Docs](https://developer.mozilla.org/en-US/)

### Topics

       Form, Value, Submit

### Sample Image

![Sample One](./Pic12.png)

### Tasks

     To Search a topic in the MDN Search bar.
     First add a text to search in the search bar and then hit the submit search button to search the docs using DOM

### Output

![Output](./Pic13.png)

### Code
```
function search(t){
     let input = document.querySelector("#hp-search-input"); 
     input.value = t; 
     let form = document.querySelector("#hp-search-form"); 
     form.submit();
     }
search("Css Selector");
```

### Change OUTPUT

![Change Output](./change1213.png)

8. Webiste Name: [Google](https://www.google.com/)

### Topics

       Remove Elements

### Sample Image

![Sample One](./Pic14.png)

### Tasks

     Remove alternate languages from the home page languages listed

### Output

![Output](./Pic15.png)

### Code

```
let total = document.querySelectorAll("#SIvCob a");
for(i = 0; i < total.length; i++){
     if (i % 2 == 0){
          total[i].remove()
          }
     }
```

### Change OUTPUT

![Change Output](./change1415.png)

9. Webiste Name: [Code Wars](https://www.codewars.com/)

### Topics

       Change Font Family, Color of Text.

### Sample Image

![Sample One](./Pic16.png)

### Tasks

    Change the font family of the text to monospace and text color to the logo’s background color.

### Output

![Output](./Pic17.png)

### Code
```
document.querySelector(".display-heading-1").style.color = "#b1361e";
document.querySelector(".display-heading-1").style.fontFamily = "monospace";
```

### Change OUTPUT

![Change Output](./change1617.png)

10. Webiste Name: [Freecodecamp](https://www.freecodecamp.org/)

### Topics

       querySelector, mouseover, click eventListener,  callback function, style,

### Sample Image

![Sample One](./Pic18.png)

### Tasks

    Target the button and change background colour on mouseover

### Output

![Output](./Pic19.png)

### Code

```
document.querySelector(".btn-cta-big .login-btn-text").addEventListener("mouseover", function(){
     document.querySelector(".btn-cta-big .login-btn-text").style.backgroundColor = "red";
     })
```

### Change OUTPUT

![Change Output](./change1819.png)

11. Webiste Name: [realme](https://www.realme.com/in/)

### Topics

       querySelector,style,background-image

### Sample Image

![Sample One](./Pic20.png)

### Tasks

    change the realme logo to ineuron logo

### Output

![Output](./Pic21.png)

### Code

```
document.querySelector(".logo .icon-logo").style.backgroundImage = "url('https://ineuron.ai/images/ineuron-logo.png')";
```

### Change OUTPUT

![Change Output](./change2021.png)

12. Webiste Name: [Github](https://github.com/)

### Topics

       querySelector,style,background-Color

### Sample Image

![Sample One](./Pic22.png)

### Tasks

     change the background colour of the button to blue.

### Output

![Output](./Pic23.png)

### Code

```
document.querySelector(".btn-primary").style.backgroundColor = "Blue";
```

### Change OUTPUT

![Change Output](./change2223.png)

13. Webiste Name: [Hackerrank](https://www.hackerrank.com/)

### Topics

       querySelector,innerHtml

### Sample Image

![Sample One](./Pic24.png)

### Tasks

Target the top description and change “Matching developers with great companies” to ‘JSBOOTCAMP“.

### Output

![Output](./Pic25.png)

### Code

```
document.querySelector(".fl-heading-text").innerText = "JSBOOTCAMP";
```

### Change OUTPUT

![Change Output](./change2425.png)

14. Webiste Name: [Asus](https://www.asus.com/in/)

### Topics

      querySelector,style,font-size

### Sample Image

![Sample One](./Pic26.png)

### Tasks

       change the fontsize of “Hot Deals” to 80px

### Output

![Output](./Pic27.png)

### Code

```
document.querySelector(".HotDealsAll__Heading__2fIbe").style.fontSize = "80px";
```

### Change OUTPUT

![Change Output](./change2627.png)

15. Webiste Name: [Dell](https://www.dell.com/en-in/shop/deals/laptop-deals?gacd=10415953-9016-5761040-285981356-0&dgc=ST&gclid=Cj0KCQjwguGYBhDRARIsAHgRm4-XUDMhhVNyHXb3s1gY4ZBzORr_d9Se-buhJwy7asyUe7YdqEA11eEaAt6UEALw_wcB&gclsrc=aw.ds&nclid=BxjBlpBQsX6pjSHh-L8YYSU77EpfXRkG1AGMB5Wbeu386ykspfrPDnfx_DdFau20)

### Topics

      querySelector,style.textAlign

### Sample Image

![Sample One](./Pic28.png)

### Tasks

       Convert the text “G15 Gaming Laptop” from left to right

### Output

![Output](./Pic29.png)

### Code

```
document.querySelector(".ps-title").style.textAlign = "right";
```

### Change OUTPUT

![Change Output](./change2829.png)

16. Webiste Name: [Vercel](https://vercel.com/)

### Topics

     querySelector,innerHTMl

### Sample Image

![Sample One](./Pic30.png)

### Tasks

      change the heading “Start with the developer” to “Start with Scratch”

### Output

![Output](./Pic31.png)

### Code

```
document.querySelector(".section-title_title__VEDfK").innerText = "Start With Scratch";
```

### Change OUTPUT

![Change Output](./change3031.png)

17. Webiste Name: [Sony](https://www.sony.co.in/)

### Topics

    querySelector,innerHTMl

### Sample Image

![Sample One](./Pic33.png)

### Tasks

     change the button text To current Date.

### Output

![Output](./Pic32.png)

### Code

```
document.querySelector(".btn-container").innerHTML = new Date;
```

### Change OUTPUT

![Change Output](./change3233.png)

18. Webiste Name: [Philips](https://www.philips.co.in/)

### Topics

     querySelector,style,backgroundcolor

### Sample Image

![Sample One](./Pic34.png)

### Tasks

    change the background colour blue to orange

### Output

![Output](./Pic35.png)

### Code

```
document.querySelector(".p-f03-footer-container").style.background = "orange";
```

### Change OUTPUT

![Change Output](./change3435.png)

19. Webiste Name: [Canon](https://in.canon/)

### Topics

          querySelector,src

### Sample Image

![Sample One](./Pic36.png)

### Tasks

    extract the canon logo

### Output

![Output](./Pic37.png)

### Code

```
document.querySelector(".navbar-brand .logo").innerText = "https://in.canon/assets/brand/logo-300-002e45a4aec98fd92899838da9d5560f.png";
```

### Change OUTPUT

![Change Output](./change3637.png)

20. Webiste Name: [Oppo](https://www.oppo.com/in/)

### Topics

          querySelector,style,color

### Sample Image

![Sample One](./Pic38.png)

### Tasks

      Change the description colour black to orange

### Output

![Output](./Pic39.png)

### Code

```
document.querySelector(".desc").style.color = "orange";
```

### Change OUTPUT

![Change Output](./change3839.png)
