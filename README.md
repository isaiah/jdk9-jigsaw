# Build Jigsaw with ant

Most code taken from [jigsaw quick-start](http://openjdk.java.net/projects/jigsaw/quick-start)

Demonstrate how to build Jigsaw projects with apache ant, and it's
restrictions at the current state.

## install JDK9 and apache ant

Tested with latest trunk of ant, I'm assuming 1.9.9+ should work, but please
report if it doesn't

Check environement:

```shell
ant check
```

If it doesn't report any error then go to each individual examples and run:

```shell
ant
```

The original shell scripts from upstream a kept as reference.

## Examples covered

- Session 1: Jigsaw Introduction
   - Greetings [./session-1-jigsaw-intro/01_Greetings](./session-1-jigsaw-intro/01_Greetings)
   - Greetings world [./session-1-jigsaw-intro/02_GreetingsWorld](./session-1-jigsaw-intro/02_GreetingsWorld)
   - Multi-module compilation [./session-1-jigsaw-intro/03_MultiModuleCompilation](./session-1-jigsaw-intro/03_MultiModuleCompilation)
   - Packaging [./session-1-jigsaw-intro/04_Packaging](./session-1-jigsaw-intro/04_Packaging)
   - Missing requires [./session-1-jigsaw-intro/05_Missing_requires](./session-1-jigsaw-intro/05_Missing_requires)
   - Missing exports [./session-1-jigsaw-intro/05_Missing_exports](./session-1-jigsaw-intro/05_Missing_exports)
   - Services [./session-1-jigsaw-intro/06_Services](./session-1-jigsaw-intro/06_Services)
   - javac --patch-module option [./session-1-jigsaw-intro/07_patch_module_option](session-1-jigsaw-intro/07_patch_module_option)
   - Modules export conflict [./session-1-jigsaw-intro/08_ModulesExportConflict](session-1-jigsaw-intro/08_ModulesExportConflict)

- Session 2: JLink
   - JLink example [./session-2-jlink/01_JLink](session-2-jlink/01_JLink)
   - JMod example [./session-2-jlink/02_JMod](session-2-jlink/02_JMod) 

- Session 3: JShell
   - JShell quick tutorial [./session-3-jshell/](./session-3-jshell/)
   - JShell examples [./session-3-jshell/JShell-Examples](./session-3-jshell/JShell-Examples)
   - shellFX [./session-3-jshell/shellFX/](./session-3-jshell/shellFX/)
   - teamshell [./session-3-jshell/teamshell/](./session-3-jshell/teamshell/)
        
## Must reads
- [The State of the Module System](http://openjdk.java.net/projects/jigsaw/spec/sotms/)
- [JEP 261](http://openjdk.java.net/jeps/261)
- [http://mail.openjdk.java.net/pipermail/adoption-discuss/2015-September/001053.html](http://mail.openjdk.java.net/pipermail/adoption-discuss/2015-September/001053.html) <br/>
- [http://mail.openjdk.java.net/pipermail/adoption-discuss/2015-September/001056.html](http://mail.openjdk.java.net/pipermail/adoption-discuss/2015-September/001056.html)

## Other resources
- [JDK 9 / Jigsaw Resources](./Java-9-Resources.md)
- [Adopt OpenJDK homepage](https://adoptopenjdk.java.net/)
- [Adopt OpenJDK: Getting Started Kit](http://bit.ly/1NUkPWw)
