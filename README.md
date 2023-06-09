# Compose-CustomerDetailsService

Fully stand-alone containerized Docker composition. Automatically pulls latest source for Java-CustomerDetailsService and Angular-CustomerDetailsService from GitHub. Be sure to have Docker installed and run the commands below to build and run.

## Clone and Compose

Make sure to clone recursively, as the dockerfiles are pulled from submodules' Compose branches.
  
`git clone https://github.com/ThatDRW/Compose-CustomerDetailsService.git --recurse-submodules`
  
Then open a terminal in the `Compose-CustomerDetailsService` directory and run:
  
`docker compose up --build`
  
Then navigate to:
  
`http://localhost:4200`