pipeline {
  agent any
  stages {
    stage('Setup WP CLI') {
      steps {
        sh '''curl -O https://raw.githubusercontent.com/wp-cli/builds/gh-pages/phar/wp-cli.phar
php wp-cli.phar --info
chmod +x wp-cli.phar
mv wp-cli.phar /usr/local/bin/wp'''
      }
    }

  }
}