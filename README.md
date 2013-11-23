Dudie maven repository
======================

```
<project>
...
  <repositories>
    <repository>
      <id>dudie-github-releases</id>
      <name>Dudie releases hosted on Github</name>
      <url>https://raw.github.com/dudie/maven-repository/releases</url>
      <releases>
        <enabled>true</enabled>
      </releases>
      <snapshots>
        <enabled>false</enabled>
      </snapshots>
    </repository>
    <repository>
      <id>dudie-github-snapshots</id>
      <name>Dudie snapshots hosted on Github</name>
      <url>https://raw.github.com/dudie/maven-repository/snapshots</url>
      <releases>
        <enabled>false</enabled>
      </releases>
      <snapshots>
        <enabled>true</enabled>
      </snapshots>
    </repository>
  </repositories>
...
</project>
```
