# Personal Academic Website

This repository contains the source code for a personal academic website created using Quarto. The website showcases the academic profile of a recent PhD graduate, including personal information, research interests, publications, teaching experience, and contact details.

## Project Structure

The project is organized as follows:

- **_quarto.yml**: Configuration file for the Quarto website, defining the site's metadata and structure.
- **index.qmd**: The homepage featuring a personal introduction, research directions, and a welcome message.
- **about.qmd**: Detailed information about the individual, including educational background and personal history.
- **cv.qmd**: A comprehensive CV showcasing educational background, work experience, and skills.
- **publications.qmd**: A list of academic publications, including papers and conference proceedings.
- **research.qmd**: Description of research areas and projects, highlighting research achievements and future plans.
- **teaching.qmd**: Overview of teaching experience, including courses taught and teaching philosophy.
- **contact.qmd**: Contact information, including email and social media links.
- **styles.css**: Custom styles for enhancing the website's appearance, ensuring a modern and academic look.
- **_site/**: Directory for storing the generated static website files.
- **images/**: Directory containing images, including a profile picture.
- **.gitignore**: Specifies files and directories to be ignored by version control.
- **README.md**: This file, providing an overview and usage instructions for the project.

## Deployment

To deploy the website on GitHub Pages, follow these steps:

1. Ensure that your repository is named `<username>.github.io`, where `<username>` is your GitHub username.
2. Build the site using Quarto by running the following command in your terminal:
   ```
   quarto render
   ```
3. Push the contents of the `_site` directory to the `main` branch of your repository:
   ```
   git add _site
   git commit -m "Deploy website"
   git subtree push --prefix _site origin main
   ```
4. Visit `https://<username>.github.io` to see your deployed website.

## Acknowledgments

This project was inspired by the need for a professional online presence for academics and researchers. It utilizes Quarto for easy content management and modern web design.