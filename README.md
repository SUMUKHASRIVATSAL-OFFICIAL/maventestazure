- task: PublishBuildArtifacts@1
  inputs:
    pathToPublish: '$(System.DefaultWorkingDirectory)/mvnprog'   
    artifactName: 'drop'
    publishLocation: 'Container'
