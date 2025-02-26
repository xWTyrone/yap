YAP 7.2.1 Reference Manual                         {#mainpage}
====================

![The YAP Logo](docs/img/icons/yap_128x128x32.png)

NOTE: this version of YAP is still experimental, documentation may be missing or out of date.

## Introduction

This document provides User information on version 7.2.1
of YAP (<em>Yet Another Prolog</em>). The YAP Prolog System is a
high-performance Prolog compiler developed at Universidade do Porto.

The manual is organised as follows:

+ @ref  INSTALL

+ @subpage run

+ @subpage load_files

+ @ref Builtins

+ @ref YapExtensions

+ @ref YAPLibrary

+ @subpage packages

+ @subpage YAPProgramming

+ @subpage fli_c_cxx


\author Vitor Santos Costa,
\author Luís Damas,
\author Rogério Reis
\author Rúben Azevedo


© 1989-2020 L. Damas, V. Santos Costa and Universidade
do Porto.
Permission is granted to make and distribute verbatim copies of this manual provided the copyright notice and this permission notice are preserved on all copies.
Permission is granted to copy and distribute modified versions of this manual under the conditions for verbatim copying, provided that the entire resulting derived work is distributed under the terms of a permission notice identical to this one.
Permission is granted to copy and distribute translations of this manual into another language, under the above conditions for modified versions.

This manual was written by Vítor Santos Costa,
Luís Damas, Rogério Reis, and Rúben Azevedo. The
manual is largely based on the DECsystem-10 Prolog User's Manual by
D.L. Bowen, L. Byrd, F. C. N. Pereira, L. M. Pereira, and
D. H. D. Warren. We have  used comments from the Edinburgh Prolog
library written by R. O'Keefe. Documentation from many built-ins is
originally from the SWI-Prolog manual, with the gracious authorization
from
Jan Wielemaker. We would also like to gratefully
acknowledge the contributions from Ashwin Srinivasian.

@defgroup Builtins YAP Core Built-ins
@ingroup mainpage
@{

This chapter describes the core built-in predicates that control the
execution of Prolog programs, provide fundamental functionality such
as term manipulation or arithmetic, and support interaction with
external resources.

<!-- - Execution Control: -->
<!--   + @ref YAPControl -->
<!--   + @ref TopLevel -->
<!--   + @ref CatchThrow -->
<!--   + @ref Undefined_Procedures -->
<!--   + @ref Sets -->
<!--   + @ref Profiling -->
<!--   + @ref Call_Counting -->
<!--   + @ref SystemHacking -->
<!--   + @ref YAPStyleChecker -->


<!-- - Meta-programming and Term Manipulation: -->
<!--   + @ref Predicates_on_Atoms -->
<!--   + @ref ComparingTerms -->

<!-- - Arithmetic -->
<!--   + @ref arithmetic -->
<!--   + @ref CompiledExpression -->

<!-- - Data-Base and Global Status -->
<!--   + @ref Database -->
<!--   + @ref YAPPredDecls -->
<!--   + @ref Internal_Database -->
<!--   + @ref YAPFlags -->
<!--   + @ref Statistics -->

<!-- - Input/Output and OS -->
<!--   + @ref YAPOS -->
<!-- 	+ @ref absf -->
<!--   + @ref pathconf -->

<!-- - Other -->
<!--   + @ref Dialects -->
<!--   + @ref SWI-error -->
<!--   + @ref Grammars -->
<!--   + @ref MixBag -->
<!--   + @ref Ypp -->

Many of the predicates described here have been standardised by the International Standard Organization.
 The corresponding standartised subset of Prolog also known as ISO-Prolog.

In the description of the arguments of predicates the following
notation will be used:

+ a preceding plus sign will denote an argument as an "input argument" - the argument is read, not written, and it cannot be a free variable at the time of the call;

+ a preceding minus sign will denote an "output argument";

+ an argument with no preceding symbol can be used in both ways.

@}


@defgroup YAPLibrary YAP Library
@ingroup mainpage
@{


 the library_directory path (set by the
  `LIBDIR` variable in the Makefile for YAP). Several files in the
  library are originally from the public-domain Edinburgh Prolog library.

@}



@defgroup YapExtensions Extensions to core Prolog
@ingroup mainpage
@{

YAP includes a number of extensions over the original Prolog
language.


@}

@page YAPProgramming Programming in YAP


<!-- @page packages Packages for YAP -->
