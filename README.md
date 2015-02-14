# NAME

CPAN::Test::Dummy::Perl5::DifferentProvides - Dist with non-matching provides

# DESCRIPTION

This distribution has a valid `provides` entry in META.json and
META.yml with mis-matching entries with the `.pm` files.

- CPAN::Test::Dummy::Perl5::DifferentProvides::A exists in the file package, but does not in `provides`.
- CPAN::Test::Dummy::Perl5::DifferentProvides::B exists in `provides`, but the file does not exist.

# AUTHOR

Tatsuhiko Miyagawa <miyagawa@bulknews.net>

# COPYRIGHT

Copyright 2015- Tatsuhiko Miyagawa

# LICENSE

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.

# SEE ALSO

[CPAN::Test::Dummy::Perl5::EmptyProvides](https://metacpan.org/pod/CPAN::Test::Dummy::Perl5::EmptyProvides)
