pipeline{
    // 任何一个代理可用就可以执行
    agent any

    // 定义一些环境信息

    // 定义流水线的加工过程
    stages {
        //  流水线的所有阶段

        // 1.编译
        stage('代码编译'){
            steps {
            // 要做的事情
            echo "代码编译..."
            sh 'pwd && ls -alh'
            sh 'printenv'
            }
        }

        // 2.测试
        stage('测试'){
            steps {
            echo "测试..."
            }
        }
        // 3.打包
        stage('打包'){
            steps {
            echo "打包..."
            }
        }
        // 4.部署
        stage('部署'){
            steps {
            echo "部署..."
            }
        }
    }
}