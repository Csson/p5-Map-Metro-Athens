# NAME

Map::Metro::Plugin::Map::Athens - Map::Metro map for Athens

# SYNOPSIS

    use Map::Metro;
    my $graph = Map::Metro->new('Athens')->parse;

# DESCRIPTION

See [Map::Metro](https://metacpan.org/pod/Map::Metro) for usage information.

# Status

As of 2015-01-02 it contains the three Metro lines and the two Proastiakos lines. See [wikipedia](https://en.wikipedia.org/wiki/Athens_metro).

Notes:

\* Larissa Station (Athens Railway Station) is considered to be the same station on both M2 and P1.

\* The Irakleio station on P2 is called 'Irakleio P' to separate it from the Irakleio station on M1.

See [Map::Metro::Plugin::Map::Athens::Lines](https://metacpan.org/pod/Map::Metro::Plugin::Map::Athens::Lines).

# AUTHOR

Erik Carlsson <info@code301.com>

# COPYRIGHT

Copyright 2015 - Erik Carlsson

# LICENSE

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.
