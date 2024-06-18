## Dependencies

This project uses the `opencsv` and `commons-lang3` libraries for CSV file processing. 

To use these libraries, you need to download the `opencsv.jar` and `commons-lang3.jar` files from their respective repositories or include them as dependencies in your build management tool.

For `opencsv`, download it from [opencsv official website](https://mvnrepository.com/artifact/com.opencsv/opencsv/5.9).

For `commons-lang3`, download it from [commons-lang Maven repository](https://mvnrepository.com/artifact/org.apache.commons/commons-lang3/3.14.0).

Alternatively, you can add these dependencies to your build tool:

For Maven, add the following to your `pom.xml`:

```xml
<dependencies>
    <dependency>
        <groupId>com.opencsv</groupId>
        <artifactId>opencsv</artifactId>
        <version>5.9</version>
    </dependency>
    <dependency>
        <groupId>org.apache.commons</groupId>
        <artifactId>commons-lang3</artifactId>
        <version>3.14.0</version>
    </dependency>
</dependencies>

For Gradle, include this in your build.gradle:

dependencies {
    implementation 'com.opencsv:opencsv:5.9'
    implementation 'org.apache.commons:commons-lang3:3.14.0'
}
