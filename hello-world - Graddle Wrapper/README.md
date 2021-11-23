# Gradle Wrapper
## <u> Working with multiple versions </u>
- Gradle API can include breaking changes in between major versions.
- Maintaining multiple Gradle installations on a developer machine is not convenient.


## <u> The Graddle Wrapper </u>
> Gradle offers a cure for this problem, the Gradle Wrapper.
- Gradle Wrapper is a set of files checked into the SCM alonside source code.
- Standardizes compatible Gradle version for a project.
- Automatically downloads the Gradle distribution with defined version.


## <u> Benefits </u>
- Developers do not need to install the Gradle runtime.
- Developers can check out project source code and build right away.
- Gradle works the same way of continous integration servers.

---
For more, check documentation [here][1].

---
**Further readings**:
1. How/when to generate Gradle wrapper files? ([link][2])
2. Why should the Gradle Wrapper be committed to VCS? ([link][3])


[1]: https://docs.gradle.org/current/userguide/gradle_wrapper.html (docs.gradle.org)
[2]: https://stackoverflow.com/questions/25769536/how-when-to-generate-gradle-wrapper-files (stackoverflow)
[3]: https://stackoverflow.com/questions/20348451/why-should-the-gradle-wrapper-be-committed-to-vcs (stackoverflow)