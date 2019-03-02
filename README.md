# gitolly

[![MIT License][License Image]][License]
[![Python Version][Python Image]][Python]
![Project Status: Active][Project Status Image]

                             .-'''-.                              
                            '   _    \  .---..---.                
             .--.         /   /` '.   \ |   ||   |                
      .--./) |__|        .   |     \  ' |   ||   |.-.          .- 
     /.''\\  .--.     .| |   '      |  '|   ||   | \ \        / / 
    | |  | | |  |   .' |_\    \     / / |   ||   |  \ \      / /  
     \`-' /  |  | .'     |`.   ` ..' /  |   ||   |   \ \    / /   
     /("'`   |  |'--.  .-'   '-...-'`   |   ||   |    \ \  / /    
     \ '---. |  |   |  |                |   ||   |     \ `  /     
      /'""'.\|__|   |  |                |   ||   |      \  /      
     ||     ||      |  '.'              '---''---'      / /       
     \'. __//       |   /                           |`-' /        
      `'---'        `'-'                             '..'         

    created by "Alex Barreto" <axbarreto [at] tuta [dot] io>
    Version: 1.0.2

    usage: 'python -m gitolly -u'
                Username and password will be prompted.

    Clone all your Github repositories.

    optional arguments:
      -h, --help            show this help message and exit
      -u USER, --user USER  Your github username
      -p PASSWORD, --password PASSWORD
                            Github password
      -t TOKEN, --token TOKEN
                            Github OAuth token
      -o ORG, --org ORG     Organisation/team. User used by default.
      -d DEST, --dest DEST  Destination directory. Created if doesn't exist.
                            [curr_dir]
      --nopull              Don't pull if repository exists. [false]

    example: 'python -m gitolly -u $GITUSER -t $TOKEN -o $ORG -d $TT_DIR'


##### Licence
MIT

[License Image]: https://img.shields.io/badge/license-MIT-brightgreen.svg "MIT License"
[License]: https://github.com/axbaretto/gitolly/blob/master/LICENSE "MIT License"

[Python Image]: https://img.shields.io/badge/python-3.5-blue.svg "Python Version: 3.5"
[Python]: https://docs.python.org/3.5/whatsnew/changelog.html#python-3-5-0-final "Python 3.5 Changelog" 

[Project Status Image]: https://img.shields.io/badge/project-active-green.svg "Project Status: Active"
