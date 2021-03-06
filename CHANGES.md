2017-02-09, Version 2.0.0
=========================

 * mac: Fix compilation errors (Howard Hellyer)

 * Rename nodereport module to node-report (Richard Chamberlain)

 * Fix source directory for install target (Richard Lau)

 * aix: skip command line check for test-fatal-error (Richard Lau)

 * Add the list of library files loaded by the process to nodereport. (Howard Hellyer)

 * docs: AIX supports triggering on USR2 signal (Richard Lau)

 * Fix behaviour on exception to match node default (Richard Chamberlain)

 * Adds the command line used to start the node process to nodereport. (Howard Hellyer)

 * Opt-in hooks and signal by default (Richard Chamberlain)

 * Fix for clang warning: libstdc++ is deprecated (Richard Chamberlain)


2016-12-12, Version 1.0.7
=========================

 * Fix version reporting in NodeReport section (Richard Lau)

 * Fix fprintf calls on Windows (Richard Lau)


2016-11-18, Version 1.0.6
=========================

 * Fix test-exception.js for PPC (Richard Lau)

 * Improve README.md (Jeremiah Senkpiel)

 * Improvement to Windows version reporting (Richard Lau)

 * Convert testcases to use tap (Richard Lau)


2016-11-10, Version 1.0.5
=========================

 * Fix for failure in fatal error (OOM) test (Richard Chamberlain)

 * Add support for nodereport on AIX (Richard Chamberlain)

 * Deleting AUTHORS file. (Richard Chamberlain)

 * Correct Javascript to JavaScript in README.md (Richard Chamberlain)

 * Correct upper-case NPM, should be lower-case (Richard Chamberlain)

 * Remove specific URLs for NPM (Richard Chamberlain)

 * Add MAINTAINER.md file to document NPM release procedure (Richard Chamberlain)

 * Set/correct package metadata in package.json (Richard Chamberlain)

 * README documentation improvements (Richard Chamberlain)

 * .gitignore the test autorun log file (Sam Roberts)

 * test: require this module using correct syntax (Sam Roberts)

 * .npmignore: do not pack unnecessary files (Sam Roberts)

 * .gitignore: ignore npm ephemera and node reports (Sam Roberts)

 * Need to define __STDC_FORMAT_MACROS for some glibc versions (Richard Chamberlain)


2016-10-28, Version 1.0.4
=========================

 * First release!
