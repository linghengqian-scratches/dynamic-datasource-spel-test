- Serving https://github.com/oracle/graalvm-reachability-metadata/pull/154
  and https://github.com/baomidou/dynamic-datasource-spring-boot-starter/issues/471
- Execute the following command to see the error.
```shell
git clone git@github.com:linghengqian/dynamic-datasource-spel-test.git
cd ./dynamic-datasource-spel-test
sdk use java 22.3.r17-grl
./gradlew clean test
```