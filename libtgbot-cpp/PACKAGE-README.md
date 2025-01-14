# libtgbot-cpp - [![GitHub contributors](https://img

This is a `build2` package for the [`<UPSTREAM-NAME>`](https://<UPSTREAM-URL>)
C++ library. It provides <SUMMARY-OF-FUNCTIONALITY>.


## Usage

To start using `libtgbot-cpp` in your project, add the following `depends`
value to your `manifest`, adjusting the version constraint as appropriate:

```
depends: libtgbot-cpp ^<VERSION>
```

Then import the library in your `buildfile`:

```
import libs = libtgbot-cpp%lib{<TARGET>}
```


## Importable targets

This package provides the following importable targets:

```
lib{<TARGET>}
```

<DESCRIPTION-OF-IMPORTABLE-TARGETS>


## Configuration variables

This package provides the following configuration variables:

```
[bool] config.libtgbot_cpp.<VARIABLE> ?= false
```

<DESCRIPTION-OF-CONFIG-VARIABLES>
