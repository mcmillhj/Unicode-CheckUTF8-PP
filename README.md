[![Build Status](https://travis-ci.org/mcmillhj/Unicode-CheckUTF8-PP.svg?branch=master)](https://travis-ci.org/mcmillhj/Unicode-CheckUTF8-PP)
[![Coverage Status](https://coveralls.io/repos/mcmillhj/Unicode-CheckUTF8-PP/badge.svg?branch=master)](https://coveralls.io/r/mcmillhj/Unicode-CheckUTF8-PP?branch=master)
[![Kwalitee status](http://cpants.cpanauthors.org/dist/Unicode-CheckUTF8-PP.png)](http://cpants.charsbar.org/dist/overview/Unicode-CheckUTF8-PP)

# NAME

Unicode::CheckUTF8::PP - Pure Perl implementation of Unicode::CheckUTF8

# VERSION

version 0.003

# SYNOPSIS

    use Unicode::CheckUTF8::PP qw(is_utf8);
    my $is_ok = is_utf8($scalar);

# DESCRIPTION 

Pure Perl implementation of [Unicode::CheckUTF8](https://metacpan.org/pod/Unicode::CheckUTF8), almost all logic was directly ported from that module. The target audience of this module are users who would like the functionality of Unicode::CheckUTF8, but don't have access to a C compiler or lack permissions to compile on their systems (for whatever reason)

# METHODS

- `is_utf8`

    Determines whether a Perl scalar is a UTF8 compliant string

        returns 1 if the supplied string is UTF8 compliant 
        returns 0 otherwise

# AUTHOR 

Based entirely on [Unicode::CheckUTF8](https://metacpan.org/pod/Unicode::CheckUTF8), written by Brad Fitzpatrick

# AUTHOR

Hunter McMillen &lt;mcmillhj@gmail.com>

# COPYRIGHT AND LICENSE

This software is copyright (c) 2016 by Hunter McMillen.

This is free software; you can redistribute it and/or modify it under
the same terms as the Perl 5 programming language system itself.
