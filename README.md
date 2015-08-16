# fdroid-git
A tool for setting up and hosting an F-Droid repository using github pages to host.

fdroid-git personal repository tool
================================
This tool helps developers host their own applications by posting them to 
github pages for download.  

        -d \ --directory
                Work in this directory, uses current directory by default
        -o \ --origin
                URL of the repository
        -c \ --codename
                Codename you want to use, defaults is \"testing\"
        -s \ --sources
                Folder with the packages to include in the repo
        -t \ --description
                Name of the override file
        -m \ --message
                Message to include in the commit
        -c \ --check
                Make sure the dependencies are installed
        -r \ --reset
                Re-generate all components of the repository
        -u \ --user \ --org \ --organization
                Us as user/organization page, post page to master branch
        -h \ --help
                Display this help message        