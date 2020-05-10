# Assigment 3: Static Website

To deploy a static website using [Hugo](https://gohugo.io) (a static web site generator) and host it on GitHub Project Pages.

## Static web site generator

A static web site generator is an application that takes plain text files and compiles them to HTML files.


### Hugo
![](https://d33wubrfki0l68.cloudfront.net/c38c7334cc3f23585738e40334284fddcaf03d5e/2e17c/images/hugo-logo-wide.svg)

Hugo is a static HTML and CSS website generator written in Go. It is optimized for speed, ease of use, and configurability. Hugo takes a directory with content and templates and renders them into a full HTML website.

Hugo relies on Markdown files with front matter for metadata, and you can run Hugo from any directory. This works well for shared hosts and other systems where you don’t have a privileged account.

Hugo renders a typical website of moderate size in a fraction of a second. A good rule of thumb is that each piece of content renders in around 1 millisecond.

Hugo is designed to work well for any kind of website including blogs, tumbles, and docs.

## Instructions

1. [Install Hugo](https://gohugo.io/getting-started/installing)
2. Create a repository in [GitHub](https://github.com)
   - repository name: `static_website`
3. Clone the repository to your computer
   `git clone https://github.com/<USERNAME>/static_website.git`
4. [Create a webiste using Hugo](https://gohugo.io/getting-started/quick-start/)
   - Website name: `static_website`
     `hugo new site static_website`
5. Customise your website, for example:
   - Add another theme
   - Create extra sections
   - Add posts
   - ...
6. Test your website, start the Hugo server
   `hugo server -D`
   Navigate to your new site at http://localhost:1313/
7. Build static pages
   - Add this line `publishDir = "docs"` to the `config.toml` file (set the publish directory)
   - Generate pages
     `hugo -D`
8. Commit & Push your changes to the remote directory
9. [Setup GitHub Project Pages](https://gohugo.io/hosting-and-deployment/hosting-on-github/#github-project-pages)
10. Test it
   `https://<USERNAME>.github.io/static_website/`

### Configuration file

Example of a `config.toml` file:

```
   baseURL = "https://<USERNAME>.github.io/static_website/"
   languageCode = "en-us"
   title = "MSIG XXI - My New Hugo Site"
   theme = "ananke"
   publishDir = "docs"
```

- Replace the `<USERNAME>` for your actual GitHub username
- `publishDir = "docs"` is mandatory to work on GithHub Project pages

## Deliverable

- Link to the website
- Screenshot of the contributors' activity

## Collaboration
