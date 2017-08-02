node{
    stage("checkout"){
        git 'https://github.com/asquarezone/CSharpAssesment.git'
    }
    stage("build"){
    //bat "\"${tool 'MSBuild'}\" Assignments/ConsoleApplication1/ConsoleApplication1.sln" 


        bat "dir"

        bat '''
        
        set PATH=%PATH%;C:\\Program Files (x86)\\MSBuild\\14.0\\Bin 
        
        msbuild Assignments/ConsoleApplication1/ConsoleApplication1.sln
        '''
        
        
        
        
          println(env.JENKINS_HOME);
    }
}