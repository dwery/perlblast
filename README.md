# perlblast
a Perl-Tk implementation of galblast/atfblast that uses the parport device (even via USB!)

I came to write it because I wanted to be able to program GAL's a simple way in Linux. galblast.exe and atfblast.exe are both
running on Windows only. 'perlblast' runs unmodified on Linux and Windows, provided that Perl is installed.

The file README2 is the main information about the project. As said I am neither a (very) good Perl programmer or very fluent in English. So help on both area's will be grateful.

'perlblast' at this moment still has some rough ends but I like to add refinements from myself and others over time. The basic functionality is there.

Known issues's:
- some values after user edit are not applied to the programming itself

The fuse checksum is generated and checked correctly. As is the file checksum now.

For use on Windows: install StrawBerry Perl.
with cpan: install Tk and install Time::HiRes

The 'parport' access method works without any problem on Windows XP. You need to have an LPT port on your system of course.
