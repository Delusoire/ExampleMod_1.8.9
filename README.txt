./gradlew setupDecompWorkspace # or setupDevWorkspace setupCIWorkspace

# import build.gradle in IDEA

./gradlew genIntellijRuns

# in case of problems
./gradlew --refresh-dependencies
./gradlew clean
