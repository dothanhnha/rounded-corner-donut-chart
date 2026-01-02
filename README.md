
## Gradle

**Step 1.** Add it in your root settings.gradle at the end of repositories
```Gradle
    dependencyResolutionManagement {
    		repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
    		repositories {
    			mavenCentral()
    			maven { url 'https://jitpack.io' }
    		}
    	}
```
**Step 2.** Add the dependency
```Gradle
    dependencies {
	        implementation 'com.github.dothanhnha:rounded-corner-donut-chart:lastest-version'
	    }
```

## Gradle.kts

**Step 1.** Add it in your settings.gradle.kts at the end of repositories:
```Gradle
  dependencyResolutionManagement {
  		repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
  		repositories {
  			mavenCentral()
  			maven { url = uri("https://jitpack.io") }
  		}
  	}
```
**Step 2.** Add the dependency
```Gradle
  dependencies {
  	        implementation("com.github.dothanhnha:rounded-corner-donut-chart:lastest-version")
  	}
```
## Maven

**Step 1.** Add to pom.xml
```xml
  <repositories>
		<repository>
		    <id>jitpack.io</id>
		    <url>https://jitpack.io</url>
		</repository>
	</repositories>
```
**Step 2.** Add the dependency
```xml
  <dependency>
	    <groupId>com.github.dothanhnha</groupId>
	    <artifactId>rounded-corner-donut-chart</artifactId>
	    <version>lastest-version</version>
	</dependency>
```
