#!groovy
node {
    env.SKIP_UNIT_TESTS=true
    env.DISABLE_SONARQUBE = 1
    env.SKIP_SECURITY=1
    StandardBuild()
}
