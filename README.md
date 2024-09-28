# Jenkins-Project1
Started by user BHarshitha
Running as SYSTEM
Building in workspace /var/lib/jenkins/workspace/build-job
The recommended git tool is: NONE
using credential 2b64d311-8179-4d9d-a4db-8580cf1f8d94
 > git rev-parse --resolve-git-dir /var/lib/jenkins/workspace/build-job/.git # timeout=10
Fetching changes from the remote Git repository
 > git config remote.origin.url https://github.com/BHarshitha44/DevOps-practice-2.git # timeout=10
Fetching upstream changes from https://github.com/BHarshitha44/DevOps-practice-2.git
 > git --version # timeout=10
 > git --version # 'git version 2.40.1'
using GIT_ASKPASS to set credentials 
 > git fetch --tags --force --progress -- https://github.com/BHarshitha44/DevOps-practice-2.git +refs/heads/*:refs/remotes/origin/* # timeout=10
Seen branch in repository origin/main
Seen 1 remote branch
 > git show-ref --tags -d # timeout=10
Checking out Revision 422560e73bd75b1680962b0157262a16b39d6e9d (origin/main)
 > git config core.sparsecheckout # timeout=10
 > git checkout -f 422560e73bd75b1680962b0157262a16b39d6e9d # timeout=10
Commit message: "Maven Webb application"
 > git rev-list --no-walk 422560e73bd75b1680962b0157262a16b39d6e9d # timeout=10
[build-job] $ /var/lib/jenkins/tools/hudson.tasks.Maven_MavenInstallation/Maven_software/bin/mvn clean compile package
[INFO] Scanning for projects...
[INFO] 
[INFO] ----------------< in.InternshipStudio:02-Maven-WebApp >-----------------
[INFO] Building 02-Maven-WebApp Maven Webapp 1.0-SNAPSHOT
[INFO]   from pom.xml
[INFO] --------------------------------[ war ]---------------------------------
[INFO] 
[INFO] --- clean:3.2.0:clean (default-clean) @ 02-Maven-WebApp ---
[INFO] Deleting /var/lib/jenkins/workspace/build-job/target
[INFO] 
[INFO] --- resources:3.3.1:resources (default-resources) @ 02-Maven-WebApp ---
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
[INFO] skip non existing resourceDirectory /var/lib/jenkins/workspace/build-job/src/main/resources
[INFO] 
[INFO] --- compiler:3.11.0:compile (default-compile) @ 02-Maven-WebApp ---
[INFO] No sources to compile
[INFO] 
[INFO] --- resources:3.3.1:resources (default-resources) @ 02-Maven-WebApp ---
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
[INFO] skip non existing resourceDirectory /var/lib/jenkins/workspace/build-job/src/main/resources
[INFO] 
[INFO] --- compiler:3.11.0:compile (default-compile) @ 02-Maven-WebApp ---
[INFO] No sources to compile
[INFO] 
[INFO] --- resources:3.3.1:testResources (default-testResources) @ 02-Maven-WebApp ---
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
[INFO] skip non existing resourceDirectory /var/lib/jenkins/workspace/build-job/src/test/resources
[INFO] 
[INFO] --- compiler:3.11.0:testCompile (default-testCompile) @ 02-Maven-WebApp ---
[INFO] No sources to compile
[INFO] 
[INFO] --- surefire:3.2.2:test (default-test) @ 02-Maven-WebApp ---
[INFO] No tests to run.
[INFO] 
[INFO] --- war:3.4.0:war (default-war) @ 02-Maven-WebApp ---
[INFO] Packaging webapp
[INFO] Assembling webapp [02-Maven-WebApp] in [/var/lib/jenkins/workspace/build-job/target/02-Maven-WebApp]
[INFO] Processing war project
[INFO] Copying webapp resources [/var/lib/jenkins/workspace/build-job/src/main/webapp]
[INFO] Building war: /var/lib/jenkins/workspace/build-job/target/02-Maven-WebApp.war
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  2.195 s
[INFO] Finished at: 2024-09-21T15:22:57Z
[INFO] ------------------------------------------------------------------------
Finished: SUCCESS
