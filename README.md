
This repository has the code for the tech blog for https://marmita.pt.

# Using

1. [Install Hugo](https://gohugo.io/overview/installing/)
2. Clone this repository
```bash
git clone https://github.com/tcarreira/marmitaderedon-blog.git marmita-blog
cd marmita-blog
```
3. Run Hugo and access http://localhost:1313/
```bash
hugo server 
```
4. Articles should be published inside `/content/post`:

# Publishing to production (making it live)

Every push to the `main` branch gets automatically deployed to production (in a couple of minutes).  
This uses [Github Actions](https://docs.github.com/actions) to host the website using [Github Pages](https://pages.github.com/) to do it.
