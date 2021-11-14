# Portfolio Website
This is my ***[Portfolio website](https://quirky-kilby-7ef6c7.netlify.app)*** , Link is ***[https://quirky-kilby-7ef6c7.netlify.app](https://quirky-kilby-7ef6c7.netlify.app)***.

***[GitHub repository](https://github.com/sam-lee-py/Portfolio)***  for this website is ***[https://github.com/sam-lee-py/Portfolio](https://github.com/sam-lee-py/Portfolio)***.

## Purpose
This website is used to show my work **porfoliov, previous experience, hobbies** and some **blogs**.

## Sitemap
Here is the Sitemap for this websit(use mermaid):
```mermaid
    graph TB
    index(index) --> portfolio(portfolio)
    index(index) --> blog(blog)
    index(index) --> contact(contact)
    portfolio(portfolio) --> project(project)
    portfolio(portfolio) --> aboutme(about me)
    blog(blog) --> blog5(5 blogs with blog list)
    contact(contact) --> email(E-mail form)
    contact(contact) --> link(CV.pdf and officail webist link)
```
![sitemap](./docs/sitemap.png)

## Functionality / Features
This website is deveoped by ***HTML and CSS***.

#### Contains 4 HTML page:
- idex page
- portfolio page
- blog page
- contact page

#### SRI Use sha512 sha384 sha256 
```html
    <link rel="stylesheet" href="./style/main.css" integrity="sha512-ZId9KhM9BFGWnU9/hA8FiF7IzMYYBwXqy2PkKWCCayVaWKEIzT4nEE11PCco8Ds7uCfzAXE9in74gtTazFkzEw== sha384-ig/qF4YeX224oa3kN9ime4M8eH+4AyYLdyJeyZLJrvXuhXqwml91ZU91gCaklywv sha256-bD7DA/aVtmVjCXqfkxnmNwybyeQwrnkSa6kVK3qq1kI=" crossorigin="anonymous" /> 
```

#### All the animation in this website use CSS animation. For example,
```css
    animation: logo-tracking 10s infinite;

    @keyframes logo-tracking {
    0% {letter-spacing: -0.5em; filter: blur(6px);}
    25% {letter-spacing: 0.1em; filter: blur(0px);}
    75% {letter-spacing: 0.1em; filter: blur(0px);}
    100% {letter-spacing: -0.5em; filter: blur(6px);}
}
```

### Target audience
This website target audience is for the **cooperater** and **employer**.

### Screenshots
- **Index page**
    ![index page](./docs/index_page.png)
- **Portfolio page**
    ![Portfolio page](./docs/portfolio_page.png)
- **Blog page**
    ![Blog page](./docs/blog_page.png)
- **Contact page**
    ![Contact page](./docs/contact_page.png)

### Tech stack
#### HTML
Hypertext Markup Language (HTML) is used for structuring and placing content. 
#### CSS
Cascading Style Sheets (CSS) determines how the content displays. It controls colors, fonts, layout, etc. 

### Style
#### Color use:
- ```#DDDDDD```
- ```#222831```
- ```#30475E```
- ```#F05454```
- ```#222831```
- ```#717d8c```
- ```#a7b5bb```

#### Icon use:
- ![x-icon](./docs/icon.png)
- ![CV-icon](./docs/CV_icon.png)
- ![email-icon](./docs/email_icon.png)
- ![github-icon](./docs/github_icon.png)
- ![Linkedin-icon](./docs/Linkedin_icon.png)
