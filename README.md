Maven NOTICE Generation Plugin
===================

Generates Apache style NOTICE files.

```xml
<plugin>
  <groupId>org.jasig.maven</groupId>
  <artifactId>maven-notice-plugin</artifactId>
    <version>1.0.5</version>
    <configuration>
        <noticeTemplate>${jasig-notice-template-url}</noticeTemplate>
        <licenseMapping>
            <param>${jasig-license-lookup-url}</param>
        </licenseMapping>
    </configuration>
</plugin>
```

# Release

The `trunk` branch is used for development. Use `master` to cut a release (merge with `trunk` first)
