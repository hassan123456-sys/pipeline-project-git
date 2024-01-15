pipeline {

agent any

stages{

Stage("compile"){

    steps{

        sh "javac Test.java"
    }

}
Stage("run"){


    steps{
        sh "java Test"
    }
}

}



}