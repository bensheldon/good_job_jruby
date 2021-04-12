# GoodJob JRuby Experiments

A bare Ruby on Rails application for exploring JRuby compatibility.

## Building with warbler

```bash
# Build
MAVEN_REPO=https://repo1.maven.org/maven2 bundle exec warble runnable executable war

# Run the webserver
java -jar good_job_jruby_experiments.war

# Run a console command
java -jar good_job_jruby_experiments.war -S rails db:version
```
