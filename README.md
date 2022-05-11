### Welcome to Today I Learn
Documentation -> https://amolwank.github.io/todayIlearn/

Test 1.1.1.1
Test 2.2.2.2
Test 3 3
### Documentation Authoring how-to:

Please use draw.io for all diagrams and commit them and their .PNG exports to docs/images

### Steps to run the documentation locally:

 1. Make sure you have [python](https://www.python.org/downloads) 3.7+ and [mkdocs](https://www.mkdocs.org/) on your local laptop. (ONCE)
 1. Install mkdocs & MCMP Theme for mkdocs (ONCE):

        pip3 install mkdocs
        git clone repo as needed (ONCE)
        git pull (AS NEEDED)
        pip3 install -e <local dir to where clone of repo>> (ONCE)
        
 1. Clone this repo (ONCE):
 
        git clone 
    
 1. Update this repo (as often as needed):
 
        git pull
    
 1. Make changes to markdown files in the /docs folder as needed
 1. Update mkdocs.yml with new items
 1. Add draw.io diagrams to /docs/Images (if needed)
 2. Build the documentation:
 
        mkdocs build --clean --strict
    
 3. Serve the documentation locally to test changes (can use other port if conflict)
 
        mkdocs serve -s -a 127.0.0.1:8000
        
    Use http://127.0.0.1:8000/ to test documentation
    
 4. Commit the changes  OR Open a pull request with changes and share the PR with peers to approve & merge. 
 5. To deploy your changes run:
        
        mkdocs gh-deploy

1. Then check this [URL](https://pages.github.com/todayilearn/) to see your changes. 

Other links:
- [MkDocs user guide](https://www.mkdocs.org/user-guide/)
