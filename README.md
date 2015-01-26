# NAME

Map::Metro::Plugin::Map::Athens - Map::Metro map for Athens

# VERSION

Version 0.1101, released 2015-01-26.

# SYNOPSIS

    use Map::Metro;
    my $graph = Map::Metro->new('Athens')->parse;

Or:

    $ map-metro.pl route Athens Marousi Panormou

# DESCRIPTION

See [Map::Metro](https://metacpan.org/pod/Map::Metro) for usage information.

# Status

As of 2015-01-02 it contains the three Metro lines and the two Proastiakos lines. See [wikipedia](https://en.wikipedia.org/wiki/Athens_metro).

Notes:

\* Larissa Station (Athens Railway Station) is considered to be the same station on both M2 and P1.

\* The Irakleio station on P2 is called 'Irakleio P' to separate it from the Irakleio station on M1.

See [Map::Metro::Plugin::Map::Athens::Lines](https://metacpan.org/pod/Map::Metro::Plugin::Map::Athens::Lines).

# SOURCE

Source repository is at [https://github.com/Csson/p5-Map-Metro-Athens](https://github.com/Csson/p5-Map-Metro-Athens).

# HOMEPAGE

Please visit the project's homepage at [https://metacpan.org/release/Map-Metro-Plugin-Map-Athens](https://metacpan.org/release/Map-Metro-Plugin-Map-Athens).

# AUTHOR

Erik Carlsson <info@code301.com>

# COPYRIGHT AND LICENSE

This software is copyright (c) 2015 by Erik Carlsson <info@code301.com>.

This is free software; you can redistribute it and/or modify it under
the same terms as the Perl 5 programming language system itself.
