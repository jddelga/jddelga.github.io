To update your portfolio with a new entry, follow these steps:

1. **Create a New Page in the Portfolio Directory**
   - Navigate to the `portfolio` directory in your project.
   - Create a new Markdown file (`.md`) for your new portfolio entry. The file name should be descriptive, for example, `my-new-project.md`.
   - Open the newly created file and start with the YAML front matter. Here's a basic template:
     ```` markdown
     ``` 
     ---
     title: "Power Tools"
     excerpt: "Explore the world of power tools and their essential role in crafting, construction, and DIY projects."
     header:
     teaser: assets/img/powertools.jpg
     ---
     
   - After the front matter, add the content of your portfolio entry. Include images, code snippets, or any relevant information about the project.

2. **Update the Index.md with the New Entry**
   - Open the `index.md` file located in the root directory.
   - Add a new entry for your project in the format that matches the existing entries. Typically, this includes a title, a brief description, and a link to the new page you just created. For example:
     ```
     - image_path: assets/img/powertools.jpg
     alt: "Power Tools"
     title: "Power Tools"
     excerpt: "Explore the world of power tools and their essential role in crafting, construction, and DIY projects."
     ```
   - Save your changes to `index.md`.

3. **Commit and Push Your Changes**
   - Once you're satisfied with your new portfolio entry and the update to `index.md`, commit your changes to your Git repository.
   - Push the changes to your remote repository to update your live portfolio site.

Remember to check your site after updating to ensure everything is displaying as expected.