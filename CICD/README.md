**Build management**

    Tools
        Maven
        Gradle
            Test suites 
                https://docs.gradle.org/current/userguide/jvm_test_suite_plugin.html
            Gradle test vs check
                https://baeldung.com/gradle-test-vs-check
            Compile, Implementation and testImplementation
                https://www.baeldung.com/gradle-dependency-management
                https://www.baeldung.com/gradle-implementation-vs-compile
                Compile - Using dependencies during compile-time classpath and runtime classpath
                Implementation - Using dependencies during runtime classpath
                testImplementation - Required to compile tests
                Compile-time (conversion to machine code) and runtime (execution of machine code)
        Bazel (mostly for monorepos)
        Renovate bot 
            Automated dependency updates
            https://github.com/renovatebot/renovate

**Deployment**

    Container
    Docker
    Kubernetes
    Containers vs VMs - https://aws.amazon.com/compare/the-difference-between-containers-and-virtual-machines/

**Testing**

    Unit tests
        Code coverage via Jacoco https://docs.gradle.org/current/userguide/jacoco_plugin.html
        Junit
        Mockito 
        Mock vs Spy
            Mock is a dummy object (fake object) and Spy is a partial mock (real object)
            https://stackoverflow.com/questions/28295625/mockito-spy-vs-mock
    Mutation tests 
        https://www.baeldung.com/java-mutation-testing-with-pitest
    Integrating tests
    E2e tests
    Regression tests

    

