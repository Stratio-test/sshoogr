@Library('libpipelines@preproduction') _

hose {
    EMAIL = 'lgutierrez'
    DEPLOYONPRS = false
    BUILDTOOL = 'gradle'
  
    

    
    DEV = { config ->
        doCompile(config)
        doPackage(config)
        doDeploy(config)

    }
