# "Horiseon Refactor"

## Table of Contents


- [Description](#description)
- [Technologies](#technologies)
- [Deployed Link](#link)
- [Usage](#usage)
- [User Information](#userinformation)
- [Credits](#credits)
- [License](#license)

## Description
Horiseon's previous code base for their website did not meet accessibilty standards. For instance if someone was to interact with their website using a screen reader, images would not have a descriptive caption. 

Now when examining Horiseons website's html and css you will see semantic elements, improving the accessibility of Horiseon's website, as well as optimizing its compatibility with search engines. The accompanying .css style guide was also updated with new class tags and semantic elements to consolidate code. Other small changes include giving the website an appropriiate title and fixing a broken navigation link. 
## Technologies Used

- HTML
- CSS

## Deployed Link

[Horiseon Website](https://mtwence.github.io/horiseon-refactor/)

## Usage

### Website Landing Page

![Horiseon homepage](/assets/images/website.png)

### Code Snippets
Semantic html elements were subsituted for standard `<div>` elements.

#### Previous Header:
```ruby
 <div class="header">
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
```
<br>

#### Semantically Updated Header: 
```ruby
<header class="header">
        <h1>Hori<span class="seo">seo</span>n</h1>
        <nav> 
            <a class=nav1 href="#search-engine-optimization">Search Engine Optimization<a>    
            <a class=nav1 href="#online-reputation-management">Online Reputation Management<a>
            <a class=nav1 href="#social-media-marketing">Social Media Marketing</a>   
        </nav>
    </header>
```
<br>

Images were given descriptive <alt> attributes for accessibility with screen readers

#### Previous Image Element:
```ruby
<img src="./assets/images/brand-awareness.png"/>
```
<br>

#### Updated Image Element:
```ruby
<img src="./assets/images/brand-awareness.png" alt="lightbulb blinkig"/>
```
<br>

## User Information

### **Michael Wence**
[LinkedIn](https://www.linkedin.com/in/michael-wence/) |
[GitHub](https://github.com/mtwence)

## Credits

UCB - Coding Bootcamp


## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

© 2022 Michael Wence. All Rights Reserved.