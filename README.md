while (<INPUT>) {
	chomp($_);
	if (/^Strain/) {
		($rubbish,$strain) = split(/\s\W{3}\s/,$_);	
	}
	if (/^DOB/) {
		($rubbish,$dob) = split(/OB\s?\W{3}\s?/,$_);	
	}
