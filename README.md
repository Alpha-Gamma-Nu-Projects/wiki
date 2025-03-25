# AGNU Wiki

Hosted site: https://alpha-gamma-nu-projects.github.io/wiki/

This is a simple static blogging website for AGNU.

Built with [Hugo](https://gohugo.io/) and the [Hello Friend NG](https://themes.gohugo.io/hugo-theme-hello-friend-ng/) theme.

## Contributing

### Prerequisites

1. Fork this repository and clone it to your local machine.
2. Install [Hugo](https://gohugo.io/getting-started/installing/).
3. Install [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).



### Creating a Post

1. Create a new markdown file in the `content/posts` directory:
    ```sh
    hugo new content/posts/<your-post>.md
    ```

2. Edit the markdown file with your content.
    > [!IMPORTANT]  
    > Make sure to always set `draft: false` in posts to have them rendered on the updated website.

3. Run the Hugo server to preview your changes:
    ```sh
    hugo server
    ```

4. Commit your changes and submit a pull request.

### Changing Configuration

1. Edit the `config.toml` file to change the website configuration.
2. Run the Hugo server to preview your changes:
    ```sh
    hugo server
    ```
3. Commit your changes and submit a pull request.

### Resources

- [Getting Started with Hello Friend NG](https://themes.gohugo.io/themes/hugo-theme-hello-friend-ng/#how-to-configure)
- [Hugo Documentation](https://gohugo.io/documentation/)

Thank you for contributing!
