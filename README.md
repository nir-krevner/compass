Usage: compass help [command]

Description:
  The Compass Stylesheet Authoring Framework helps you
  build and maintain your stylesheets and makes it easy
  for you to use stylesheet libraries provided by others.

Donating:
  Compass is charityware. If you find it useful please make
  a tax deductable donation: http://umdf.org/compass

To get help on a particular command please specify the command.

Primary Commands:
  * clean	- Remove generated files and the sass cache
  * compile	- Compile Sass stylesheets to CSS
  * create	- Create a new compass project
  * init	- Add compass to an existing project
  * watch	- Compile Sass stylesheets to CSS when they change
Other Commands:
  * config	- Generate a configuration file for the provided command line options.
  * extension	- Manage the list of compass extensions on your system
  * frameworks	- List the available frameworks
  * help	- Get help on a compass command or extension
  * imports	- Emit an imports suitable for passing to the sass command-line.
  * install	- Install an extension's pattern into your compass project
  * interactive	- Interactively evaluate SassScript
  * sprite	- Generate an import for your sprites.
  * stats	- Report statistics about your stylesheets
  * unpack	- Copy an extension into your extensions folder.
  * validate	- Validate your generated css.
  * version	- Print out version information

Available Frameworks & Patterns:

  * compass
    - compass/ellipsis  - Plugin for cross-browser ellipsis truncated text.
    - compass/extension - Generate a compass extension.
    - compass/project   - The default project layout.

Global Options:
    -r, --require LIBRARY            Require the given ruby LIBRARY before running commands.
                                       This is used to access compass plugins without having a
                                       project configuration file.
    -l, --load FRAMEWORK_DIR         Load the framework or extensions found in the FRAMEWORK directory.
    -L, --load-all FRAMEWORKS_DIR    Load all the frameworks or extensions found in the FRAMEWORKS_DIR directory.
    -I, --import-path IMPORT_PATH    Makes files under the IMPORT_PATH folder findable by Sass's @import directive.
    -q, --quiet                      Quiet mode.
        --trace                      Show a full stacktrace on error
        --force                      Allows compass to overwrite existing files.
        --boring                     Turn off colorized output.
    -?, -h, --help                   Show this message
