clean:
	./gradlew clean
run-dist:
	./build/install/app/bin/app
check-updates:
	./gradlew dependencyUpdates
lint:
	./gradlew checkstyleMain checkstyleTest
build:
	./gradlew clean build
.PHONY: build
test:
	./gradlew test
	./gradlew jacocoTestReport
reports:
	./gradlew jacocoTestReport
