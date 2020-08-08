# 01-horiseon
# Code Refactor Starter Code

URLs

Deployed Application: 
    https://rogers0404.github.io/01-horiseon/

GitHub Repository:
    https://github.com/rogers0404/01-horiseon.git


Commits:

First Assignment in UCF Code Boot Camp

1. Adding Comments to style.css and index.html

2. Checking the proper identation and reorganizing in both file

3. Header Section:
- Eliminated the original div tag section by Header Tag in index.html file
- Eliminated class .header by element header in style.css file

4. Fotter Section:
- Eliminated the original div tag section by Footer Tag in index.html file
- Eliminated class .footer by element header in style.css file

5. Content Section
- Eliminated Classes 
    * .search-engine-optimization
    * .online-reputation-management
    * .social-media-marketing
    Reasons: they have the same name like ankles in the header section and they have the same attributes each other
    Replaced by .content div {} declaration

- Eliminated Classes / Selectors
    * .search-engine-optimization img
    * .online-reputation-management img
    * .social-media-marketing img
    Reasons: they have the same attributes each other
    Replaced by .content div img {} declaration


- Eliminated Classes / Selectors
    * .search-engine-optimization h2
    * .online-reputation-management h2
    * .social-media-marketing h2
    Reasons: they have the same attributes each other
    replaced by .content div h2 {} declaration

6. Benefits Section
- Eliminated Classes 
    * .benefit-lead
    * .benefit-brand
    * .benefit-cost
    Reasons: they have the same attributes each other
    replaced by .benefits div {} declaration

- Eliminated Classes / Selectors
    * .benefit-lead h3
    * .benefit-brand h3
    * .benefit-cost h3
    Reasons: they have the same attributes each other
    replaced by .benefits div h3{} declaration

- Eliminated Classes / Selectors
    * .benefit-lead img
    * .benefit-brand img
    * .benefit-cost img
    Reasons: they have the same attributes each other
    replaced by .benefits div img{} declaration

- Adding style to p tag inside Benefits Section, 
    Reason: to match with the mock up given to the challenge
    .benefits div p{
                    font-size: 16px;
                    margin: auto 20px;
}

7. Adding unique ID attribute in element DIV in section content, because it does not work originally
    "id=search-engine-optimization"

8. Adding Title: Horiseon, Search Engine for Business



Screenshots:

![](./assets/images/01-html-css-git-homework-demo.png)