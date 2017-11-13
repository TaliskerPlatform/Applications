## Talisker: Applications

## Copyright 2017 Mo McRoberts.
##
##  Licensed under the Apache License, Version 2.0 (the "License");
##  you may not use this file except in compliance with the License.
##  You may obtain a copy of the License at
##
##      http://www.apache.org/licenses/LICENSE-2.0
##
##  Unless required by applicable law or agreed to in writing, software
##  distributed under the License is distributed on an "AS IS" BASIS,
##  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
##  See the License for the specific language governing permissions and
##  limitations under the License.

AC_INIT([Applications],[develop])

AC_CONFIG_AUX_DIR([BuildScripts])
AC_CONFIG_MACRO_DIR([M4])

TAL_CHECK_DOMAINS

AM_INIT_AUTOMAKE([foreign])
AM_MAINTAINER_MODE

apps_subdirs=''
games_subdirs=''
utils_subdirs=''
demos_subdirs=''

TAL_CONFIG_SUBDIR([Utilities/Start-up],,,[AS_VAR_APPEND([utils_subdirs],[" Start-up"])])

AC_SUBST([apps_subdirs])
AC_SUBST([games_subdirs])
AC_SUBST([utils_subdirs])
AC_SUBST([demos_subdirs])

AC_CONFIG_FILES([
Makefile
Demos/Makefile
Games/Makefile
Utilities/Makefile
])

AC_OUTPUT
