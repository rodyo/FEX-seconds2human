[![View Convert seconds to human readable string(s) on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/22977-convert-seconds-to-human-readable-string-s)

[![Donate to Rody](https://i.stack.imgur.com/bneea.png)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=4M7RMVNMKAXXQ&source=url)

# FEX-seconds2human

This function converts a (usually large) amount of seconds to human-readable string. For example,
>> str = seconds2human(1463456.3)
str =
'About 2 weeks and 2 days.'
You may also call the function with a second input argument; either 'short' (the default) or 'full'. This determines the level of detail returned in the string:
>> str = seconds2human(1463456.3, 'full')
str =
'2 weeks, 2 days, 22 hours, 30 minutes, 56 seconds.'

The 'short' format returns only the two largest units of time.

Furthermore, [secs] may be an NxM-matrix, in which case the output is an NxM cell array of the corresponding strings.

If you like this work, please consider [a donation](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=4M7RMVNMKAXXQ&source=url). 
