node {
    checkout([
         $class: 'GitSCM',
         branches: [[name: '*/master']],
         doGenerateSubmoduleConfigurations: scm.doGenerateSubmoduleConfigurations,
         extensions: scm.extensions,
         userRemoteConfigs: scm.userRemoteConfigs
    ])
 }
