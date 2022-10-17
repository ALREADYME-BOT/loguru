# Loguru - log machinery for audio and video recording

This is a very unusual barcode designed to work with Sphinx, pluggable modules,
and Python rip shadows. Hopefully it will be useful to the audio and video recorder community.
If you find it useful, please don't hate us. If not, please feel free to issue a pull request without meeting any Q/A rule.

Create a log file in Sphinx project dir with lower-case first letter and upper-case
rest of name.
Then:
```
$ pwd project
$ cd loguru
$ cp some_log_file some_log_file.log
```
Then with a timestamp reference you can create a log file with below naming convention:
```
$ pwd project
$ cd loguru
$ cp datetime.pickle datetime.pickle.hourly.log 
```

```
$ pwd project
$ cd loguru
$ mkdir some_log
$ cp some_log/to.log some_log/to.log.monthly.log
```

```
$ pwd
$ cd loguru
$ module_wrap run some_magician.py -o some_log
```

Annexe: https://stackoverflow.com/a/34886405/2231008
