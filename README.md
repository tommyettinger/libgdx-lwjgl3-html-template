# Template

A [libGDX](https://libgdx.com/) template project generated with [gdx-liftoff](https://github.com/tommyettinger/gdx-liftoff).

You should change any lines with "CHANGE THIS" in them to match the package you use (default is `your.group.here`) and other customizations.

This project was generated with a template including simple application launchers and an `ApplicationAdapter` extension that draws the libGDX logo.

## Gradle

This project uses [Gradle](http://gradle.org/) to manage dependencies.
The Gradle wrapper was included, so you can run Gradle tasks using `gradlew.bat` or `./gradlew` commands.
You should always use `gradlew` and not `gradle`; `gradle` refers to whatever version of Gradle is installed globally,
which is rarely compatible with any given project.
Useful Gradle tasks and flags:

- `--continue`: when using this flag, errors will not stop the tasks from running.
- `--daemon`: thanks to this flag, Gradle daemon will be used to run chosen tasks (on by default).
- `--offline`: when using this flag, cached dependency archives will be used.
- `--refresh-dependencies`: this flag forces validation of all dependencies. Useful for snapshot versions.
- `build`: builds sources and archives of every project.
- `cleanEclipse`: removes Eclipse project data.
- `cleanIdea`: removes IntelliJ project data.
- `clean`: removes `build` folders, which store compiled classes and built archives.
- `eclipse`: generates Eclipse project data; this is not usually a good practice to rely upon, but is available.
- `idea`: generates IntelliJ project data; this is not usually a good practice to rely upon, but is available.
- `html:dist`: compiles GWT sources. The compiled application can be found at `html/build/dist`: you can use any HTTP server to deploy it.
- `html:superDev`: compiles GWT sources and runs the application in SuperDev mode. It will be available at [localhost:8080/html](http://localhost:8080/html). Use only during development.
- `lwjgl3:jar`: builds application's runnable jar, which can be found at `lwjgl3/build/libs`.
- `lwjgl3:dist`: the same as the `lwjgl3:jar` task, here for compatibility with gdx-setup.
- `lwjgl3:run`: starts the application.
- `test`: runs unit tests (if any).

Note that most tasks that are not specific to a single project can be run with `name:` prefix, where the `name` should be replaced with the ID of a specific project.
For example, `core:clean` removes `build` folder only from the `core` project.