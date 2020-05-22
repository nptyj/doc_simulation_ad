This is the main repository for the whole documentation of the project doc_simulation_ad. The documentation is based on mkdocs. 

### See the documentation here:
https://www.mkdocs.org/
https://readthedocs.org/

### HomePage here:

https://doc-simulation-ad.readthedocs.io/en/latest/

### HowTO

1. git clone https://github.com/nptyj/doc_simulation_ad.git
	
2. install pip and MkDocs
	```sh
	pip install --upgrade pip
	pip install mkdocs
	```
3. MkDocs comes with a built-in dev-server that lets you preview your documentation as you work on it. Make sure you're in the same directory as the mkdocs.yml configuration file, and then start the server by running the mkdocs serve command:

	```sh
	mkdocs serve
	```
	
4. Open up http://127.0.0.1:8000/ in your browser, and you'll see the default home page being displayed.
The dev-server also supports auto-reloading, and will rebuild your documentation whenever anything in the configuration file, documentation directory, or theme directory changes. 

5. Edit the docs/index.md document and save your changes. Your browser will auto-reload and you should see your updated documentation immediately.

6. Deploying

Read the Docs(https://readthedocs.org/) offers free documentation hosting. You can import your docs using Git. It supports MkDocs out-of-the-box. Follow the instructions on their site to arrange the files in your repository properly, create an account and point it at your publicly hosted repository. If properly configured, your documentation will update each time you push commits to your public repository.