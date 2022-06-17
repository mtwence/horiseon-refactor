# Horiseon Accessibility Code Refactor

## Description 

**[Developer Profile](https://github.com/mtwence)**
**[Deployed Website](https://mtwence.github.io/hw-challenge-1/)**

Horiseon's previous code base for their website did not meet accessibilty standards. For instance if someone was to interact with their website using a screen reader images would have a descriptive caption. 

Now when examining this websites html and css you will see semantic elements, improving the accessibility of Horiseon's website, as well as optimizing its compatibility with search engines. The accompanying .css style guide was also updated with new class tags and semantic elements to consolidate code. Other small changes include giving the website an appropriiate title and fixing a broken navigation link. 

**Changes Made:**
-Semantic html elements were subsituted for standard <div> elements
    E.g. 
        Previous Header HTML:
    ' <div class="header">
        <h1>Hori<span class="seo">seo</span>n</h1>
        <div>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </div>
    </div>'


        Updated Header HTML:
    
'  <header class="header">
        <h1>Hori<span class="seo">seo</span>n</h1>
        <nav> 
            <a class=nav1 href="#search-engine-optimization">Search Engine Optimization<a>    
            <a class=nav1 href="#online-reputation-management">Online Reputation Management<a>
            <a class=nav1 href="#social-media-marketing">Social Media Marketing</a>   
        </nav>
    </header> '

-Images were given descriptive <alt> attributes for accessibility with screen readers
    E.g.
        Previous image HTML:
    '<img src="./assets/images/brand-awareness.png"/>'

          Updated image HTML:
    '<img src="./assets/images/brand-awareness.png" alt="lightbulb blinkig"/>'







## License

Licensed under the [MIT](https://github.com/microsoft/vscode/blob/main/LICENSE.txt) license



