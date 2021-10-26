REFERENCES
    https://github.com/binarythistle/S03E03---Azure-Devops-and-Terraform



SETUP
    CREATE PROJECT
        - dotnet --version
        - dotnet new 
    
    DOCKER
        - Dockerfile
        - docker build -t wyatt1231/dkr_server_pilot .
        - docker run -p 8080:80 wyatt1231/dkr_server_pilot 
        - docker ps (list of containers)
        - docker stop <img_id> (stop docker img)
        - docker push wyatt1231/dkr_server_pilot
    
    GITHUB
        - .gitignore