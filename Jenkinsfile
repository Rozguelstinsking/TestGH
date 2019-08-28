node{

  stage('stage0'){
    print('lalalaalalala0')
    checkout scm
  }
  stage('stage1'){
    print('lalalaalalalal')
  }
  stage('stage2'){
    print('lalalaalalalal2')
    sh ''' 
    
    ls -la
    
    '''
  }
  stage('stage3'){
    print('lalalaalalalal')
    
    sh '''
    
    cat README.md
    
    '''
    
  }


}
