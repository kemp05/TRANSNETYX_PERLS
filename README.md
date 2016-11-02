#!/usr/bin/perl -w
#  Parsing to produce biopsy detail file

print "hello kemp05" ;

print "\nEnter file name\n";
$input_file = <STDIN>;
chomp($input_file);
open(INPUT, $input_file) or die "\nInput file could not be found\n\n";
$index = 0;
