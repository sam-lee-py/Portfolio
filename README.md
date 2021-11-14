# Portfolio Website
This is my ***[Portfolio website](http://google.com)*** , Link is ***[http://google.com](http://google.com)***.

***[GitHub repository](https://github.com/sam-lee-py/Portfolio)***  for this website is ***[https://github.com/sam-lee-py/Portfolio](https://github.com/sam-lee-py/Portfolio)***.

## Purpose
This website is used to show my work **porfoliov, previous experience, hobbies** and some **blogs**.

## Functionality / Features
This website is deveoped by ***HTML and CSS***.

#### Contains 4 HTML page:
- idex page
- portfolio page
- blog page
- contact page

#### Color use:
- ```#DDDDDD```
- ```#222831```
- ```#30475E```
- ```#F05454```
- ```#222831```
- ```#717d8c```
- ```#a7b5bb```

#### Icon use:
- ![x-icon](./files/img/icon.png)
- ![CV-icon](./files/img/CV_icon.png)
- ![email-icon](./files/img/email_icon.png)
- ![github-icon](./files/img/github_icon.png)
- ![Linkedin-icon](./files/img/Linkedin_icon.png)

All the animation in this website use CSS animation. For example,
```css
    animation: logo-tracking 10s infinite;

    @keyframes logo-tracking {
    0% {letter-spacing: -0.5em; filter: blur(6px);}
    25% {letter-spacing: 0.1em; filter: blur(0px);}
    75% {letter-spacing: 0.1em; filter: blur(0px);}
    100% {letter-spacing: -0.5em; filter: blur(6px);}
}
```

## Sitemap
Here is the Sitemap for this websit:
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

### Target audience
This website target audience is for the **cooperater** and **employer**.

### Screenshots
- **Index page**
    ![index page](./files/img/index_page.png)
- **Portfolio page**
    ![Portfolio page](./files/img/portfolio_page.png)
- **Blog page**
    ![Blog page](./files/img/blog_page.png)
- **Contact page**
    ![Contact page](./files/img/contact_page.png)

### Tech stack
#### HTML
Hypertext Markup Language (HTML) is used for structuring and placing content. 
#### CSS
Cascading Style Sheets (CSS) determines how the content displays. It controls colors, fonts, layout, etc. 