# Heurist Ecosystem Contribution Guide

This repository serves as a portfolio of projects that build and thrive within the Heurist ecosystem. Our mission is to foster innovation and collaboration by showcasing a wide range of projects that leverage the AI models provided by Heurist Protocol.

## How to Contribute
We invite open-source developers and innovators to contribute to the Heurist Ecosystem. If you have a project that utilizes Heurist's API and wish to have it listed in our ecosystem, follow these steps to submit a pull request (PR):

### Step 1: Prepare Your Project Information
Ensure your project meets the following criteria:

- Utilizes any AI APIs provided by Heurist
- Has a publicly accessible website
- Bonus point: Has a publicly accessible repository on GitHub

### Step 2: Add Your Project to `ecosystem-list.json`
1. Fork this repository to your GitHub account.
2. Clone your forked repository locally.
3. Open the `ecosystem-list.json` file and add your project information in the format below.
4. Add your project's icon image to the icons folder. Ensure the image is optimized for web use and does not exceed 50KB in size.

`ecosystem-list.json` item format:

```
{
    "title": "Your Project Title",
    "description": "Your project description.",
    "image": "your-project-icon.png",
    "url": "https://your-project-url.com",
    "links": [
        {
            "title": "App",
            "url": "https://your-project-app-url.com"
        },
        {
            "title": "GitHub",
            "url": "https://github.com/your-github-repo"
        }
        // Add more links as needed
    ]
}
```

Prepare the following information for your project listing:

- Title: The name of your project.
- Description: A concise explanation of what your project does.
- Image: The filename of your project's icon (please ensure the icon is added to the icons folder in this repository).
- URL: The main website or landing page for your project.
- Links: Relevant links to your project's app interface, GitHub repository, documentation, social media, etc.

### Step 3: Submit Your Pull Request

Please include your project name in the PR title. In the description, briefly describe your project and how it integrates with Heurist's AI models.

## Review Process
Our team will review your submission on a weekly basis. Once approved, your project will be listed in the [Heurist Ecosystem page](https://heurist.ai/ecosystem)
