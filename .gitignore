#! /usr/bin/perl

print "Введите числа до 10-ти:\n";
chomp (@maximum_nombers = <STDIN>);
$maximum = max(@maximum_nombers);

sub max {
	if(@_ < 10 ) {
		print "Warning!!!\n";
		print "Введите числа до 10-ти:\n";
		chomp(@maximum_nombers = <STDIN>); 
		$maximum = max(@maximum_nombers);
	} 
	elsif(@_>10) {
		print "Warning!!!\n";
		print "Введите числа до 10:\n";
		chomp(@maximum_nombers = <STDIN>);
		$maximum = max(@maximum_nombers);
}
	else {
		my($first) = shift;
		foreach (@_) {
			if ($_ > $first) {
				$first = $_;
			}
		}
		$first;
	}
}

print "$maximum\n";
