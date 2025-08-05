[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/jecSxI3G)
# 📘 Assignment: HTML5 + Accessibility & SEO Basics

## Overview

This assignment will help you solidify your understanding of modern HTML5 structure while applying foundational concepts of web accessibility and search engine optimization (SEO). You’ll create a simple, semantically correct web page that prioritizes both human and machine readability—two pillars of great web design.

## Objective

Build a basic web page using HTML5 semantic tags, applying accessibility best practices and beginner-friendly SEO principles. Your final output should demonstrate a well-structured layout that supports screen readers and is optimized for discoverability.

## Guidelines

Use only HTML5. No CSS or JavaScript is required at this stage. Focus on using meaningful semantic elements to structure your page. Avoid using `<div>` or `<span>` unless absolutely necessary. Ensure your page has clearly defined sections such as a header, navigation, main content, and a footer.

Incorporate accessibility by using proper HTML5 landmarks and attributes that improve navigation for assistive technologies. Your HTML should reflect thoughtful planning of hierarchy and readability, both for users and search engines.

For SEO, emphasize the use of heading tags in the correct order, provide descriptive text, and ensure your content is both human-readable and crawler-friendly. Consider how a search engine would interpret your page in terms of structure and content clarity.

## Deliverables

A single HTML file named `index.html`. It should include:

* A semantic structure using appropriate HTML5 elements.
* Clear headings in a logical hierarchy.
* Accessibility enhancements using proper tags and attributes.
* SEO-friendly metadata and content.

## Tips

* Use HTML5 semantic tags appropriately.
* Organize content with accessibility in mind.
* Apply basic on-page SEO techniques.
* Follow clean, readable HTML code structure.

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Learn the basics of semantic HTML5, accessibility, and SEO through a simple and effective example web page." />
  <meta name="author" content="Natalia Mariana" />
  <title>HTML5 Accessibility & SEO Basics</title>
</head>
<body>

  <header>
    <h1>Welcome to HTML5 Accessibility & SEO Basics</h1>
    <nav aria-label="Main Navigation">
      <ul>
        <li><a href="#about">About This Page</a></li>
        <li><a href="#accessibility">Accessibility</a></li>
        <li><a href="#seo">SEO Fundamentals</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="about">
      <h2>About This Page</h2>
      <p>This simple example demonstrates how to structure a web page using semantic HTML5 while incorporating accessibility and search engine optimization (SEO) techniques.</p>
    </section>

    <section id="accessibility">
      <h2>Accessibility Best Practices</h2>
      <article>
        <h3>Use Semantic Landmarks</h3>
        <p>Semantic tags like <code>&lt;header&gt;</code>, <code>&lt;main&gt;</code>, and <code>&lt;footer&gt;</code> help assistive technologies understand the layout of the page.</p>
      </article>
      <article>
        <h3>ARIA Labels and Navigation</h3>
        <p>Using <code>aria-label</code> attributes improves navigation for screen readers and enhances the user experience for people with disabilities.</p>
      </article>
    </section>

    <section id="seo">
      <h2>SEO Fundamentals</h2>
      <article>
        <h3>Descriptive Headings</h3>
        <p>Clear and meaningful headings help search engines index your content and make it easier for users to navigate.</p>
      </article>
      <article>
        <h3>Meta Tags Matter</h3>
        <p>Use meta tags like <code>description</code> and <code>viewport</code> to optimize your page for search engines and mobile devices.</p>
      </article>
    </section>
  </main>

  <footer>
    <section id="contact">
      <h2>Contact</h2>
      <address>
        <p>Email: <a href="mailto:masikanatalia@gmail.com">masikanatalia@gmail.com</a></p>
        <p>GitHub: <a href="https://github.com/x3rinaa" target="_blank" rel="noopener noreferrer">x3rinaa</a></p>
      </address>
    </section>
    <p>&copy; 2025 Natalia Mariana. All rights reserved.</p>
  </footer>

</body>
</html>
