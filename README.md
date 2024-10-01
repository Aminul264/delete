 (Note: you mustinstall Laragon, Composer, and npmfirst)
 1. ClonetheRepository
 git clone <project-url>
 2. NavigatetotheProject Folder
 cd <project-folder>
 3. Install PHPDependencies
 composerinstall
 4. Install Node.js Dependencies
 npminstall
 5. SetUpEnvironmentConfiguration
 cp .env.example .env
 This copies the exampleenvironmentfile(.env.example) to a new.envfile,whichwillstore the
 project's environment-specific settings.
 6. GenerateApplication Key
 phpartisan key:generate
