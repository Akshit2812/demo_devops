pipeline {
    agent any

    stages ('sample1'){
        echo 'Building...'
        bat python demo_devops.py
            }
    stages ('sample2'){
        echo 'Using maven'
        bat mvn
    }
}
