<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Emu Market</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }

        header {
            background-color: #FFA500; /* Улбар шар өнгө */
            color: #fff;
            padding: 15px 20px;
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #fff;
            border-bottom: 1px solid #ddd;
        }

        nav a {
            text-decoration: none;
            color: #333;
            padding: 15px 20px;
            font-weight: bold;
        }

        nav a:hover {
            background-color: #FFA500;
            color: #fff;
        }

        .hero {
            text-align: center;
            padding: 50px 20px;
            background-color: #FFA500;
            color: #fff;
        }

        .hero h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
        }

        .hero p {
            font-size: 1.2em;
        }

        .section {
            padding: 20px;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Emu Market</h1>
    </header>
    <nav>
        <a href="#home">Нүүр</a>
        <a href="#about">Бидний тухай</a>
        <a href="#products">Бүтээгдэхүүн</a>
        <a href="#search">Хайлт</a>
        <a href="#contact">Холбоо барих</a>
    </nav>
    <div class="hero">
        <h1>Бүх төрлийн шинэ болон хуучин барааны онлайн дэлгүүр</h1>
        <p>Гэрээсээ орлого олох боломжийг манай платформ танд олгоно.</p>
    </div>
    <section id="about" class="section">
        <h2>Бидний тухай</h2>
        <p>Emu Market нь хувь хүн болон дэлгүүрүүдэд шинэ болон хуучин бараагаа онлайнаар борлуулах боломжийг олгодог.</p>
    </section>
    <section id="products" class="section">
        <h2>Бүтээгдэхүүн</h2>
        <p>Бүтээгдэхүүний мэдээлэл энд гарна.</p>
    </section>
    <section id="search" class="section">
        <h2>Хайлт</h2>
        <p>Та хүссэн бүтээгдэхүүнээ хайж олох боломжтой.</p>
    </section>
    <section id="contact" class="section">
        <h2>Холбоо барих</h2>
        <p>Имэйл болон бусад мэдээлэл удахгүй нэмэгдэнэ.</p>
    </section>
    <footer>
        <p>&copy; 2025 Emu Market. Бүх эрх хуулиар хамгаалагдсан.</p>
    </footer>
</body>
</html>
<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# GitHub Pages

_Create a site or blog from your GitHub repositories with GitHub Pages._

</header>

<!--
  <<< Author notes: Course start >>>
  Include start button, a note about Actions minutes,
  and tell the learner why they should take the course.
-->

## Welcome

With GitHub Pages, you can host project blogs, documentation, resumes, portfolios, or any other static content you'd like. Your GitHub repository can easily become its own website. In this course, we'll show you how to set up your own site or blog using GitHub Pages.

- **Who is this for**: Beginners, students, project maintainers, small businesses.
- **What you'll learn**: How to build a GitHub Pages site.
- **What you'll build**: We'll build a simple GitHub Pages site with a blog. We'll use [Jekyll](https://jekyllrb.com), a static site generator.
- **Prerequisites**: If you need to learn about branches, commits, and pull requests, take [Introduction to GitHub](https://github.com/skills/introduction-to-github) first.
- **How long**: This course takes less than one hour to complete.

In this course, you will:

1. Enable GitHub Pages
2. Configure your site
3. Customize your home page
4. Create a blog post
5. Merge your pull request

### How to start this course

<!-- For start course, run in JavaScript:
'https://github.com/new?' + new URLSearchParams({
  template_owner: 'skills',
  template_name: 'github-pages',
  owner: '@me',
  name: 'skills-github-pages',
  description: 'My clone repository',
  visibility: 'public',
}).toString()
-->

[![start-course](https://user-images.githubusercontent.com/1221423/235727646-4a590299-ffe5-480d-8cd5-8194ea184546.svg)](https://github.com/new?template_owner=skills&template_name=github-pages&owner=%40me&name=skills-github-pages&description=My+clone+repository&visibility=public)

1. Right-click **Start course** and open the link in a new tab.
2. In the new tab, most of the prompts will automatically fill in for you.
   - For owner, choose your personal account or an organization to host the repository.
   - We recommend creating a public repository, as private repositories will [use Actions minutes](https://docs.github.com/en/billing/managing-billing-for-github-actions/about-billing-for-github-actions).
   - Scroll down and click the **Create repository** button at the bottom of the form.
3. After your new repository is created, wait about 20 seconds, then refresh the page. Follow the step-by-step instructions in the new repository's README.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/github-pages) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
