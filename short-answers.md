## 1. Difference between Google Knowledge Graph and Google Knowledge Panel

- **Google Knowledge Graph**: This is Google’s massive database of entities (people, places, organizations, concepts) and the relationships between them. It is the underlying data structure.

- **Google Knowledge Panel**: This is the visual information box that appears on the right side (desktop) or top (mobile) of search results. It is a **display feature** powered by data from the Knowledge Graph.

In short: Knowledge Graph = the database | Knowledge Panel = the user-facing box.

## 2. How Google determines entity identity

Google determines entity identity through multiple signals:
- Consistent mentions of the same name, description, and attributes across the web.
- Structured data (Schema.org markup) especially Organization and Person schemas.
- Authoritative sources such as Wikipedia, Wikidata, and official websites.
- SameAs links connecting social profiles, websites, and directories.
- Branded search volume and user behavior.
- Co-occurrence with related entities and backlinks from trusted sites.

The stronger and more consistent these signals are, the higher Google’s confidence in the entity.

## 3. When to create Custom Post Types instead of pages

Use **Custom Post Types (CPTs)** when you need:
- Structured, repeatable content (e.g., Workspaces, Locations, Testimonials, Team Members, Case Studies).
- Custom fields and taxonomies (categories, filters).
- Separate archives and templates.
- Better organization and scalability for large amounts of similar content.

Use regular **Pages** for static, one-off content such as Homepage, About Us, Contact, Privacy Policy, etc.

## 4. Recommended plugins for speed optimization and why

**Top Recommendations:**

- **LiteSpeed Cache** (Best if using LiteSpeed server)  
  All-in-one plugin: caching, image optimization, CSS/JS minification, CDN support, and database cleanup. Very powerful and lightweight.

- **WP Rocket** (Best premium option)  
  Easiest to use with excellent performance. Great for file optimization, lazy loading, and caching. Highly recommended for best results with minimal configuration.

- **Perfmatters** (Lightweight companion)  
  Excellent for removing unnecessary scripts, deferring JS, and disabling unused features.

**Why these?**  
They directly improve Core Web Vitals, reduce load time, and help with crawl budget — all critical for indexing and SEO performance.
