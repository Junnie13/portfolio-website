# Portfolio Website

This repository contains the source code for a portfolio website built to showcase projects and blogs. The website is created using Hugo static site generator (SSG) and Blowfish theme.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Before you begin, ensure you have the following installed:

- **Hugo**: The static site generator used to build the website. Installation instructions can be found [here](https://gohugo.io/getting-started/installing/).
- **Git**: Version control system used for managing the project. Installation instructions can be found [here](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

### Installing

Follow these steps to get a development environment set up:

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/your-username/portfolio-website.git
   ```

2. Navigate into the project directory:

   ```
   cd portfolio-website
   ```

3. Initialize and update the submodule to fetch the Blowfish theme:

   ```
   git submodule init
   git submodule update
   ```

### Running the Development Server

To view the website locally, run the Hugo development server:

```
hugo server -D
```

This command will build the site and start a local web server. You can view the website by navigating to `http://localhost:1313` in your web browser.

### Customizing the Website

You can customize the website by editing the configuration file and content files:

- **Configuration**: Modify the `config.toml` file to change website settings such as site title, description, social media links, etc.
- **Content**: Add your projects and blog posts by creating Markdown files in the `content/projects` and `content/posts` directories respectively.

### Building the Website

To build the website for production, run the following command:

```
hugo
```

This will generate the static HTML files in the `public` directory, which can then be deployed to a web server.

## Hosting

This website is hosted on [Render.com](https://render.com). The deployment process is as follows:

1. Sign up for an account on Render.com if you haven't already.
2. Create a new web service on Render.com.
3. Connect the web service to your GitHub repository.
4. Configure the build settings to run the Hugo build command (`hugo`) and specify the public directory (`public`) as the output directory.
5. Deploy the website.

For more detailed instructions on how to host a Hugo website on Render.com, refer to the [official documentation](https://render.com/docs/deploy-hugo).

## Acknowledgments

- **Hugo**: The static site generator used for building the website.
- **Blowfish**: The theme used for styling the website.
