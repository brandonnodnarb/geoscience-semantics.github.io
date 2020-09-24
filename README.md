#geoscience semantics
Backend for https://geoscience-semaintics.org

#### Build the website using MkDocs
* Install mkdocs on your machine (see [https://www.mkdocs.org/#installation](installation instructions)).
* Install the gitbook theme (`pip3 install mkdocs-gitbook`).
* Run the command `mkdocs gh-deploy` (or use deploy.sh).
  * This command creates (or refreshes) the website for https://geoscience-semantics.org.
  * The command must be run from the root directory of this repo.
  * Behind the scenes, `mkdocs gh-deploy` builds HTML docs from the Markdown sources, uses the `ghp-import` tool to commit them to the `gh-pages` branch, and pushes the `gh-pages` branch to GitHub.
