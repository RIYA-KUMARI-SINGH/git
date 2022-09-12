### bostonhousepricing

### Software And Tools Requirements

1. [Github Acount](https://gihub.com)
2. [HerokuAccount](https://heroku.com)
3. [VSCODEIDE](https://code.visualstudio.com/)
4. [GitCLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

Create new environment
'''
conda create -p venv python==3.7 -y
'''

Activate new environment 
'''
conda activate venv/
'''

Deactivate new environment
'''
conda deactivate
'''

Install packages
'''
pip install -r requirements.txt
'''

configure git CLI with github repository
'''
git config --global user.name "Riya Singh"
git config --global user.email "riyasingh.199292@gmail.com"
'''

Add file git repository
'''
git add requirements.txt
'''

Add entire files to git repository
'''
git add .
'''

Check status 
'''
git status
'''

After this step files added in staging environment, now to commit files 
'''
git commit -m "This commit includes requirements.txt and readme files."
'''

Push in git repository
'''
git push origin main
'''